# Sample Interactions

This document demonstrates how the Behavioral Health Resource Assistant is intended to support behavioral health professionals using structured resource information. The examples below represent typical use cases and illustrate the assistant's expected reasoning and response structure.

---

# Scenario 1: Adult Seeking Mental Health Services

## User Input

A 32-year-old adult is experiencing symptoms of depression and anxiety after losing their job. They are looking for affordable mental health counseling and may also need assistance with food resources. They are not in immediate crisis.

---

## Expected Assistant Behavior

The assistant should:

- Recognize that the client is an adult.
- Confirm that there is no immediate safety concern.
- Recommend appropriate adult mental health providers from the project resource dataset.
- Include food assistance only if relevant resources are available.
- Explain why each recommendation was selected.
- Generate a concise referral summary.
- Provide an appropriate confidence assessment.

---

# Scenario 2: Parent Seeking Services for a Teenager

## User Input

A parent is looking for counseling services for their 15-year-old child, who has been experiencing increased anxiety since changing schools. The teenager is not in immediate crisis.

---

## Expected Assistant Behavior

The assistant should:

- Identify the client as a youth.
- Recommend youth behavioral health providers from the project resource dataset.
- Prioritize organizations that specialize in children and adolescents.
- Explain why each recommendation is appropriate.
- Generate a referral summary.
- Provide an appropriate confidence assessment.

---

# Scenario 3: Adult Seeking Substance Use Treatment

## User Input

A 41-year-old adult would like help finding outpatient treatment for alcohol use disorder. They are motivated to begin treatment but are not experiencing a medical emergency.

---

## Expected Assistant Behavior

The assistant should:

- Identify the primary need as substance use treatment.
- Recommend outpatient treatment providers from the project resource dataset.
- Explain why each provider is appropriate.
- Suggest alternative resources when applicable.
- Generate a referral summary.
- Provide an appropriate confidence assessment.

---

# Expected Response Structure

For each interaction, the assistant should organize its response using the following format:

1. Client Summary
2. Primary Recommendation
3. Alternative Resources
4. Follow-up Questions (if needed)
5. Referral Summary
6. Confidence Assessment
7. Notes

The assistant should remain grounded in the project resource dataset, avoid making assumptions, and communicate clearly, professionally, and compassionately.
