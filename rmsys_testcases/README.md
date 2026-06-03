# RMSys Test Cases Portfolio

## Overview

This repository contains structured manual QA test cases for the RMSys application, focusing on the Client → Contact tab → Phone management functionality.

The test suite demonstrates real-world QA documentation practices, including functional, UI, and validation testing.

---

## Repository Structure

RMSys_TestCases/
│
├── 01_contact_permissions.md
├── 02_phone_list_toolbar.md
├── 03_new_phone_add.md
├── 04_phone_edit.md
├── 05_phone_delete.md

---

## Test Coverage

### Contact Tab Access Control
- Verification of tab visibility based on user roles
- Authorized vs unauthorized access validation

### Phone List & Toolbar
- Validation of phone list columns
- Toolbar functionality (Add, Edit, Delete buttons)

### Add New Phone
- Field-level validation (required/optional fields)
- Input restrictions (numeric-only fields, max length validation)
- Form behavior (Save, Cancel, Close actions)

### Edit Phone
- Editing existing phone records
- Validation rules during update
- Save and discard behavior

### Delete Phone
- Delete confirmation workflow
- Record removal validation
- Cancel and close behavior

---

## Test Case Design Approach

Each test case follows a consistent structure:

- Unique Test Case ID (TC54–TC84)
- Clear functional title
- Preconditions (system state and user role)
- Step-by-step execution
- Expected results aligned with system requirements

Example format:

| Step | Expected Result |
|------|-----------------|
| Log in to RMSys | User successfully logs in |
| Open Client → Edit | Edit window opens |
| Verify Contact tab | Tab visibility is correct |

---

## Key Testing Areas

This test suite covers:

- Functional testing
- UI validation testing
- Role-based access control testing
- Positive and negative test scenarios
- Input validation (numeric, length, required fields)
- CRUD operations (Create, Read, Update, Delete)

---

## Tools & Practices

- Test case design using structured QA documentation standards
- Markdown-based documentation for version control
- GitHub for portfolio presentation and collaboration readiness

---

## Purpose

This repository demonstrates structured QA test case design for a web-based business application, focusing on clarity, maintainability, and real-world testing practices.

---

## Author

QA Engineer Portfolio
Manual Testing | Test Design | UI & Functional QA
