---
'@builder.io/sdk-angular': major
'@builder.io/sdk-react-nextjs': major
'@builder.io/sdk-qwik': major
'@builder.io/sdk-react': major
'@builder.io/sdk-react-native': major
'@builder.io/sdk-solid': major
'@builder.io/sdk-svelte': major
'@builder.io/sdk-vue': major
---

Breaking Change 🧨: `fetchEntries` and `fetchOneEntry` calls will now throw any errors thrown by `fetch`, or any non-success response returned from the Builder API.

Previously, both functions would swallow all errors and return `null`.