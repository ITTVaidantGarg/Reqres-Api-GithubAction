# FAQ - What Can This Project Do?

## About This Project

This is a **Reqres API Test Automation** project built with **.NET 8.0** and **NUnit**. It provides automated testing for the Reqres API (https://reqres.in) with continuous integration via GitHub Actions.

## What Can This Project Do?

### 🧪 API Test Automation
- **Automated API Testing**: Run comprehensive API tests for CRUD operations (Create, Read, Update, Delete)
- **Test Categories**: 
  - **Smoke Suite**: Quick validation tests for critical functionality
  - **Regression Suite**: Comprehensive tests for all features
- **Test Coverage**: Tests for GET, POST, PUT, PATCH, and DELETE operations on user endpoints

### 🚀 Continuous Integration/Delivery
- **GitHub Actions Workflows**: Automated testing on every push, pull request, and scheduled runs
- **Multiple Triggers**:
  - **Pull Requests**: Runs smoke tests automatically
  - **Push to Main**: Runs regression tests
  - **Scheduled**: Daily automatic test runs at midnight (UTC)
  - **Manual Dispatch**: Run specific test suites on-demand

### 📊 Reporting & Monitoring
- **Allure Reports**: Beautiful, interactive test reports with:
  - Test execution history
  - Detailed failure analysis
  - Test trends over time
- **GitHub Pages Deployment**: Reports automatically published to GitHub Pages
- **Test Reporter**: Inline test results in GitHub PRs/commits
- **Artifact Storage**: Test reports saved as artifacts for 7 days

### 🔧 Technical Capabilities
- **RestSharp**: HTTP client for API communication
- **NUnit**: Test framework with category-based filtering
- **Allure Integration**: Advanced reporting with severity levels and tags
- **.NET 8.0**: Modern C# features and performance
- **JSON Handling**: Newtonsoft.Json for request/response processing

## What Can I Help You With?

As an AI coding assistant, I can help you with:

### 🛠️ Code Development
- **Add New Tests**: Create tests for new API endpoints or scenarios
- **Refactor Code**: Improve code structure, reduce duplication, apply patterns
- **Fix Bugs**: Debug and resolve test failures or code issues
- **Add Features**: Implement new functionality like authentication, data-driven tests, etc.

### 📝 Documentation
- **Update README**: Add project documentation and usage instructions
- **Code Comments**: Add helpful comments to complex code sections
- **API Documentation**: Document API contracts and responses

### ⚙️ Configuration & Setup
- **CI/CD Improvements**: Enhance GitHub Actions workflows
- **Test Configuration**: Update test settings, filters, or categories
- **Add Dependencies**: Install and configure new NuGet packages
- **Environment Setup**: Configure test environments or settings

### 🧹 Code Quality
- **Code Reviews**: Analyze code for improvements and best practices
- **Security Scanning**: Run CodeQL to identify vulnerabilities
- **Performance Optimization**: Improve test execution speed
- **Code Style**: Apply consistent formatting and conventions

### 🐛 Troubleshooting
- **Debug Failures**: Analyze test failures and CI/CD issues
- **Fix Build Issues**: Resolve compilation or dependency problems
- **Investigate Logs**: Review workflow logs to identify root causes
- **Test Analysis**: Understand why tests are failing or flaky

### 🔄 Maintenance
- **Update Dependencies**: Upgrade NuGet packages to latest versions
- **Clean Up**: Remove unused code or dependencies
- **Reorganize**: Restructure project files and folders
- **Migrate**: Update to new frameworks or patterns

## How to Request Help

You can ask me to:
- ✅ "Add a new test for the login endpoint"
- ✅ "Fix the failing GetUser test"
- ✅ "Update the GitHub Actions workflow to run tests in parallel"
- ✅ "Add a README with setup instructions"
- ✅ "Refactor the test base class to reduce code duplication"
- ✅ "Add data-driven testing with multiple test cases"
- ✅ "Debug why the Allure report is not generating"
- ✅ "Update to the latest RestSharp version"
- ✅ "Add authentication tests"
- ✅ "Improve error handling in the API client"

## What I Cannot Do

⚠️ **Limitations**:
- I cannot access external APIs directly (but can write tests that do)
- I cannot create GitHub secrets or access existing ones
- I cannot force-push or rewrite git history
- I cannot access files in `.github/agents` directory
- I cannot merge pull requests or manage repository settings

## Getting Started

To work with this project:
1. **Local Development**: Clone the repository and run `dotnet test`
2. **Add Tests**: Create new test files in the `Tests` folder
3. **Run Specific Suites**: Use `--filter "TestCategory=SmokeSuite"`
4. **View Reports**: Check GitHub Pages or download Allure artifacts

## Questions?

If you have specific tasks or questions about this project, just ask! I'll:
1. Explore the codebase to understand the context
2. Create a plan with minimal, focused changes
3. Implement the changes with proper testing
4. Validate everything works correctly
5. Provide progress updates along the way

---

**Remember**: I make minimal, surgical changes to ensure reliability and maintainability. Every change is validated and tested before completion.
