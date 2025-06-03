# WeatherAPI

WeatherAPI is a C# ASP\.NET Core Web API that provides weather-related endpoints\. It uses Scalar\.AspNetCore for OpenAPI documentation and API reference generation\.

## Features

- RESTful weather endpoints
- OpenAPI \(Swagger\) documentation
- Environment\-based configuration

## Project Structure

- `WeatherAPI/Program.cs`: Main entry point and configuration
- `WeatherAPI/appsettings.Development.json`: Development environment settings
- `buildspec.yml`: Build and deployment instructions for AWS CodeBuild

## Local Development

1\. **Prerequisites**  
\- [.NET 9\.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)  
\- [Git](https://git-scm.com/)  

2\. **Restore and Run**

```bash
dotnet restore
dotnet run --project WeatherAPI