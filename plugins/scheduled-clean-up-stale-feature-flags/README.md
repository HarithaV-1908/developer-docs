---
agent_capabilities:
- Ambient Agent
availability: IDEA
description: On a monthly schedule, the agent finds launched, unused, or orphaned
  flags and proposes deletes or merges for owner approval.
domain:
- Engineering
fidelity: IDEA
name: Clean Up Stale Feature Flags
purple_chat_link: https://marketplace.moveworks.com/purple-chat?conversation=%7B%22messages%22%3A%5B%7B%22role%22%3A%22user%22%2C%22parts%22%3A%5B%7B%22richText%22%3A%22%3Cp%3EOn+a+monthly+schedule%2C+the+agent+finds+launched%2C+unused%2C+or+orphaned+flags%3C%2Fp%3E%22%7D%5D%7D%2C%7B%22role%22%3A%22assistant%22%2C%22parts%22%3A%5B%7B%22richText%22%3A%22I%27ve+identified+a+few+stale+feature+flags+that+could+be+cleaned+up.+Here+are+my+recommendations%3A%22%7D%2C%7B%22richText%22%3A%22%3Cul+xmlns%3D%5C%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxhtml%5C%22%3E%3Cli%3E%3Cb%3Efeature-v2-migration%3C%2Fb%3E+%28Launched%2C+Unused+for+%26gt%3B180+days%29%3Cul%3E%3Cli%3E%3Cb%3EProposed+Action%3A%3C%2Fb%3E+Delete%3C%2Fli%3E%3Cli%3E%3Cb%3EOwner%3A%3C%2Fb%3E+John+Doe+%28%3Ca+href%3D%5C%22mailto%3Ajohn.doe%40example.com%5C%22%3Ejohn.doe%40example.com%3C%2Fa%3E%29%3C%2Fli%3E%3C%2Ful%3E%3C%2Fli%3E%3Cli%3E%3Cb%3Eui-redesign-a-b-test%3C%2Fb%3E+%28Orphaned%2C+No+recent+changes%29%3Cul%3E%3Cli%3E%3Cb%3EProposed+Action%3A%3C%2Fb%3E+Delete%3C%2Fli%3E%3Cli%3E%3Cb%3EOwner%3A%3C%2Fb%3E+Jane+Smith+%28%3Ca+href%3D%5C%22mailto%3Ajane.smith%40example.com%5C%22%3Ejane.smith%40example.com%3C%2Fa%3E%29%3C%2Fli%3E%3C%2Ful%3E%3C%2Fli%3E%3Cli%3E%3Cb%3Ebackend-optimization-toggle%3C%2Fb%3E+%28Launched%2C+Low+usage%2C+Candidate+for+merge%29%3Cul%3E%3Cli%3E%3Cb%3EProposed+Action%3A%3C%2Fb%3E+Merge+into+codebase%3C%2Fli%3E%3Cli%3E%3Cb%3EOwner%3A%3C%2Fb%3E+Mike+Johnson+%28%3Ca+href%3D%5C%22mailto%3Amike.johnson%40example.com%5C%22%3Emike.johnson%40example.com%3C%2Fa%3E%29%3C%2Fli%3E%3C%2Ful%3E%3C%2Fli%3E%3C%2Ful%3E%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22Approve+All%22%2C%22style%22%3A%22filled%22%7D%2C%7B%22buttonText%22%3A%22Review+%26+Edit%22%2C%22style%22%3A%22outlined%22%7D%2C%7B%22buttonText%22%3A%22Cancel%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%7D%2C%7B%22role%22%3A%22assistant%22%2C%22parts%22%3A%5B%7B%22richText%22%3A%22Great%21+I%27m+ready+to+proceed+with+deleting+2+flags+in+LaunchDarkly+and+creating+a+GitHub+issue%2FPR+for+1+flag+merge.+%3Cb+xmlns%3D%5C%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxhtml%5C%22%3EDo+you+want+me+to+go+ahead%3F%3C%2Fb%3E%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22Confirm+Actions%22%2C%22style%22%3A%22filled%22%7D%2C%7B%22buttonText%22%3A%22Cancel%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%7D%2C%7B%22role%22%3A%22assistant%22%2C%22parts%22%3A%5B%7B%22reasoningSteps%22%3A%5B%7B%22status%22%3A%22pending%22%2C%22richText%22%3A%22Deleting+feature+flags+in+LaunchDarkly...%22%7D%2C%7B%22status%22%3A%22pending%22%2C%22richText%22%3A%22Creating+GitHub+issue+for+merge+recommendation...%22%7D%5D%7D%2C%7B%22richText%22%3A%22All+requested+clean-up+actions+have+been+initiated.%22%7D%5D%7D%5D%2C%22userConfig%22%3A%7B%22userName%22%3A%22Scheduled+Trigger%22%2C%22initials%22%3A%22U%22%2C%22providedIcon%22%3A%22silhoutte%22%2C%22imageUrl%22%3A%22https%3A%2F%2Fcdn-icons-png.flaticon.com%2F512%2F3652%2F3652191.png%22%7D%7D
solution_tags:
- Engineering
systems:
- launchdarkly
- github

---
