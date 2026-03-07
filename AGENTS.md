# AGENTS.md

## About this docs repo

- This repository powers the public Barekey docs on Mintlify.
- Keep content aligned with the shipping product in `usebarekey/barekey`.
- Do not document planned features as available. Put them in the roadmap instead.

## Terminology

- Use "organization" for the owning team scope.
- Use "project" for the application-level namespace inside an organization.
- Use "stage" for an environment such as `development`, `preview`, or `production`.
- Use "variable" as the default product term. Use "secret" only when the behavior is specifically secret-only.
- Current variable kinds are `secret` and `ab_roll`.
- `rollout` is planned. Do not describe it as generally available.

## Style

- Use active voice and second person.
- Keep headings in sentence case.
- Keep examples runnable.
- Prefer short code blocks over prose-heavy explanations.
- Bold UI labels such as **Create project**.
- Use code formatting for commands, paths, environment variables, JSON keys, and endpoint paths.

## Scope

Document:
- product concepts that are already in the app or API
- CLI workflows that exist in `pkg/cli`
- SDK usage that exists in `pkg/sdk`
- HTTP endpoints that exist in `pkg/convex/http.ts`

Do not document:
- internal admin-only flows
- unshipped rollout behavior as if it is live
- implementation details that create security risk beyond the public model
