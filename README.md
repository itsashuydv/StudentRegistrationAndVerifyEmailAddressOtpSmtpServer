# StudentRegistrationAndVerifyEmailAddressOtpSmtpServer
Registration Student Details and verify email address otp through Smtp Server
create a database name StudentDB and table--
CREATE TABLE Students
(
    Id INT  PRIMARY KEY,
    Name NVARCHAR(MAX) NOT NULL,
    Email NVARCHAR(MAX) NOT NULL,
    Password NVARCHAR(MAX) NOT NULL,
    IsEmailVerified BIT NOT NULL DEFAULT 0,
    OTP NVARCHAR(MAX)
);
