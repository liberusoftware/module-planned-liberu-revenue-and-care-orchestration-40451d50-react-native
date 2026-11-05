# Revenue and Care Orchestration · React Native · Expo

Independent presentation module skeleton for **Revenue and Care Orchestration**. Intended boundary: native ios/android application using react native and expo.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

**Identity review required:** documentation records multiple source identities or a naming conflict for this capability. This skeleton keeps the exact source/plan key below distinct; it does not establish equivalence, a stable package contract or safe replacement of an existing implementation.

- Capability/source key: `planned:liberu:revenue-and-care-orchestration`.
- Presentation scope: [Revenue and Care Orchestration](https://github.com/liberusoftware/documentation/blob/main/projects/liberu/react-native/revenue-and-care-orchestration.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/liberu/nextjs/revenue-and-care-orchestration.md).
- Registry identity: `@liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-react-native`.
- Foundation: [module-boilerplate-react-native](https://github.com/liberusoftware/module-boilerplate-react-native) at `b63bc1b11fe769e2e547a3f1fced6116556fe9e1`.

## Develop and verify

```bash
npm ci
npm run typecheck
npm run build
npm pack --dry-run
```

The public npm export currently provides `moduleDefinition`, explicit registration metadata. No UI screens or API calls are implemented. Add capability UI and injected contract mapping through deliberate exports.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/REACT-NATIVE.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [Liberu Platform](https://github.com/liberusoftware/project-liberu-official-mobile-react): Official sites, staff applications and platform composition.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Filament](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-filament).
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-nuxt).
- [Next.js · React](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-nextjs).
- [Flutter · Mobile](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-flutter).
- [Dart · Desktop](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-dart-desktop).
- [Dart · Mobile](https://github.com/liberusoftware/module-planned-liberu-revenue-and-care-orchestration-40451d50-dart-mobile).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
