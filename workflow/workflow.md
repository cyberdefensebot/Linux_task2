# Practical Workflow

> **Status:** Template awaiting the actual technical lab/activity document.

## Phase 1 — Analyze the activity

### What to do

Read the complete lab document and extract every explicit requirement.

### Command

No command is specified.

### Expected result

A complete list of requirements exists in `docs/task-overview.md`.

### Verification

Compare the extracted list against the original lab document.

### Evidence

No screenshot is required for this analysis step unless the lab explicitly requires one.

---

## Phase 2 — Prepare the environment

### What to do

Set up only the environment explicitly required by the actual lab.

### Command

```text
[INSERT LAB-SPECIFIC ENVIRONMENT COMMANDS]
```

### Expected result

```text
[INSERT EXPECTED RESULT FROM THE LAB]
```

### Verification

```text
[INSERT VERIFICATION COMMAND]
```

### Evidence

```text
[INSERT EVIDENCE FILENAME]
```

### Privilege

```text
[STATE: normal user / sudo / root / specific user]
```

---

## Phase 3 — Perform the required lab tasks

Repeat the following structure for every actual task.

### Task [NUMBER] — [EXACT TASK TITLE]

**What to do:**  
[Describe the required action using the lab's exact terminology.]

**Command:**
```bash
[INSERT EXACT REQUIRED COMMAND]
```

**Expected result:**
```text
[INSERT EXPECTED RESULT]
```

**Verification:**
```bash
[INSERT VERIFICATION COMMAND]
```

**Evidence:**  
[State exactly what screenshot/output proves completion.]

**Privilege:**  
[normal user / sudo / root / named user]

**Notes:**  
[Important lab-specific notes.]

---

## Phase 4 — Verification

Verify every required result using only checks supported by the lab.

```bash
[INSERT FINAL VERIFICATION COMMANDS]
```

Expected result:

```text
[INSERT ACTUAL EXPECTED RESULT]
```

---

## Phase 5 — Evidence collection

Collect genuine screenshots and terminal output.

Do not create or edit evidence to make an incomplete result appear successful.

See `evidence/README.md`.

---

## Phase 6 — Final submission

Complete:

- `submission/command-history.txt`
- `submission/final-output.txt`
- any additional submission material explicitly required by the lab.

See `submission/README.md`.

---

## Phase 7 — Final verification checklist

- [ ] Every task completed
- [ ] Every required command executed
- [ ] Every required file created
- [ ] Every required directory created
- [ ] Required permissions/ownership verified
- [ ] Required configurations verified
- [ ] Required tests completed
- [ ] Genuine screenshots captured
- [ ] Terminal output captured
- [ ] Command history saved
- [ ] Final output recorded
- [ ] Submission requirements checked
- [ ] No fabricated results included
