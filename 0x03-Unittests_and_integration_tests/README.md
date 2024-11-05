0x03. Unittests and Integration Tests

This project focuses on implementing unittests and integration tests in Python for backend code. The goal is to learn and apply testing concepts like mocking, parameterization, and fixtures, as well as differentiate between unit tests and integration tests. You’ll use the unittest framework along with unittest.mock for mocking and parameterized for parametric testing.
Learning Objectives

By the end of this project, you should be able to:

    Differentiate between unit and integration tests.
    Understand testing patterns such as mocking, parameterization, and fixtures.
    Write and run tests using unittest and unittest.mock.
    Apply memoization techniques in testing.

Resources

    unittest — Unit testing framework
    unittest.mock — mock object library
    parameterized
    Memoization

Requirements

    Python 3.7 on Ubuntu 18.04 LTS.
    pycodestyle (version 2.5) for style checks.
    All files should be executable and end with a newline.
    Each module, class, and function must have docstrings.
    All functions and coroutines must be type-annotated.

Repository Structure
alx-backend-python/
├── 0x03-Unittests_and_integration_tests/
│   ├── test_utils.py       # Unittests for utils module
│   ├── test_client.py      # Unittests and integration tests for client module
│   ├── utils.py            # Utility functions
│   ├── client.py           # Client functions for GitHub API
│   ├── fixtures.py         # Sample data for integration tests
│   └── README.md           # Project documentation

Instructions

To execute your tests, run:
$ python -m unittest path/to/test_file.py

Tasks
0. Parameterize a unit test

    Implement TestAccessNestedMap.test_access_nested_map to verify utils.access_nested_map for different inputs using @parameterized.expand.

1. Parameterize unit test exceptions

    Implement TestAccessNestedMap.test_access_nested_map_exception to verify KeyError exceptions with specific inputs.

2. Mock HTTP calls

    Implement TestGetJson.test_get_json to mock HTTP calls using unittest.mock.patch, and verify utils.get_json returns expected results.

3. Parameterize and patch

    Implement TestMemoize.test_memoize to test the memoize decorator, ensuring a_method is called only once.

4. Parameterize and patch as decorators

    Implement TestGithubOrgClient.test_org to test the GithubOrgClient.org property with mock data using decorators.

5. Mocking a property

    Implement test_public_repos_url to test GithubOrgClient._public_repos_url using a mocked payload.

6. More patching

    Implement TestGithubOrgClient.test_public_repos to unit-test GithubOrgClient.public_repos with mocked data.

7. Parameterize

    Implement TestGithubOrgClient.test_has_license to unit-test GithubOrgClient.has_license with parameterized inputs.

8. Integration test: fixtures

    Implement TestIntegrationGithubOrgClient with setUpClass and tearDownClass to mock external requests and use fixture data.

9. Integration tests (Advanced)

    Implement integration tests for GithubOrgClient.public_repos, including testing with a specific license filter.

License

This project is part of the ALX Backend Python curriculum and adheres to its usage guidelines.
