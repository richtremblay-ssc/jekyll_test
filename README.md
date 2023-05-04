# README

Shared Services Canada has built an enterprise virtual datacenter in Google Cloud to host workloads from any of the 43 departments of Government of Canada. These workloads are integrated into what we call a **Landing Zone**.

This repo will demonstrate how SSC implemented the Landing zone v2 solution available [here](https://github.com/GoogleCloudPlatform/pubsec-declarative-toolkit/tree/main/solutions/landing-zone-v2) in order to achieve **Day 0, 1 and 2** operations.

## Contents

### Architecture
[Addendum](./en/Architecture/Addendum.md)
[Repo Structure](./en/Architecture/Repository Structure.md)

## App Developer / LZ User
[Developer Guide](./en/Developer/Guide.md)

### Identity
[Identity](./en/Identity/README.md)
[Azuer AD Integration](./en/Identity/Azure AD integration.md)
[Breakglass Account Creation]()./en/Identity/Breakglass account creation.md)
[Cloud Identity](./en/Identity/Cloud Identity.md)

### Landing Zone Developer / Platform Engineer
[Gatekeeper](./en/Landing Zone Developer/gatekeeper-policies/README.md)
[Gatekeeper Testing](./en/Landing Zone Developer/gatekeeper-policies/testing/gator-cli/README.md)
[Workflow](./en/Landing Zone Developer/Workflow.md)

### Landing Zone Operator / Platform Admin

[Building](./en/Landing Zone Operations/Building.md)
[Building with Automation](./en/Landing Zone Operations/Building_Using_Automation.md)
[Changing](./en/Landing Zone Operations/Changing.md)
[Health Checks](./en/Landing Zone Operations/Health_Checks.md)
[Pipelines](./en/Landing Zone Operations/Pipelines.md)
[Repositories](./en/Landing Zone Operations/Repositories.md)

#### Onboarding

[Admin](./en/Onboarding/Admin.md)
[Application / Projects](./en/Onboarding/Application.md)
[Client](./en/Onboarding/Client.md)