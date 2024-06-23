### [S-#] TITLE (Root Cause -> Impact)

**Description:** 

**Impact:** 

**Proof of Concept:**

**Recommended Mitigation:** 

--------

# High

### [S-#] TITLE (Root Cause -> Impact)

**Description:** 

**Impact:** 

**Proof of Concept:**

**Recommended Mitigation:** 


# Medium

### [S-#] TITLE (Root Cause -> Impact)

**Description:** 

**Impact:** 

**Proof of Concept:**

**Recommended Mitigation:** 

# Low

### [S-#] TITLE (Root Cause -> Impact)

**Description:** 

**Impact:** 

**Proof of Concept:**

**Recommended Mitigation:** 

# Informational/ Non-critical

### [I-1] Test Coverage

**Description:** 
The current test coverage for the project is below 90%, indicating that several parts of the codebase are not adequately tested.

**Impact:** 
Low test coverage increases the risk of undetected bugs and potential vulnerabilities in the code, leading to unreliable software.

**Proof of Concept:**
```bash
| File                                                       | % Lines          | % Statements     | % Branches     | % Funcs        |
|------------------------------------------------------------|------------------|------------------|----------------|----------------|
| src/abstract/AStaticTokenData.sol                          | 50.00% (1/2)     | 50.00% (1/2)     | 100.00% (0/0)  | 50.00% (1/2)   |
| src/abstract/AStaticUSDCData.sol                           | 100.00% (2/2)    | 100.00% (2/2)    | 100.00% (0/0)  | 100.00% (2/2)  |
| src/abstract/AStaticWethData.sol                           | 100.00% (2/2)    | 100.00% (2/2)    | 100.00% (0/0)  | 100.00% (2/2)  |
| src/dao/VaultGuardianGovernor.sol                          | 0.00% (0/3)      | 0.00% (0/4)      | 100.00% (0/0)  | 0.00% (0/4)    |
| src/dao/VaultGuardianToken.sol                             | 66.67% (2/3)     | 50.00% (2/4)     | 100.00% (0/0)  | 50.00% (2/4)   |
| src/protocol/VaultGuardians.sol                            | 100.00% (7/7)    | 100.00% (8/8)    | 100.00% (0/0)  | 75.00% (3/4)   |
| src/protocol/VaultGuardiansBase.sol                        | 83.02% (44/53)   | 86.49% (64/74)   | 62.50% (10/16) | 93.75% (15/16) |
| src/protocol/VaultShares.sol                               | 90.38% (47/52)   | 92.06% (58/63)   | 62.50% (10/16) | 94.74% (18/19) |
| src/protocol/investableUniverseAdapters/AaveAdapter.sol    | 66.67% (4/6)     | 71.43% (5/7)     | 50.00% (1/2)   | 66.67% (2/3)   |
| src/protocol/investableUniverseAdapters/UniswapAdapter.sol | 60.87% (14/23)   | 61.29% (19/31)   | 50.00% (3/6)   | 66.67% (2/3)   |
| Total                                                      | 80.39% (123/153) | 81.73% (161/197) | 60.00% (24/40) | 79.66% (47/59) |
```

**Recommended Mitigation:** 

To improve test coverage and reduce the risk of potential bugs, we recommend the following actions:

1. **Identify Untested Code:**
   - Use the test coverage report to pinpoint the specific areas of the code that are not covered by tests.

2. **Write Additional Tests:**
   - Create unit tests for the uncovered functions, branches, and statements. Focus on critical and complex logic first.

3. **Increase Branch Coverage:**
   - Ensure that all possible branches and conditions in the code are tested to catch edge cases.

4. **Review and Refactor:**
   - Regularly review the test suite and refactor both the tests and the code to maintain high coverage and code quality.

By systematically addressing these areas, the test coverage can be improved, leading to more robust and reliable software.


