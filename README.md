# sht4 sim — workspace mode, pre-seed multi-branch merge scenario

Mirrors the f1..f4 phase of `test-pull-multi-branch-seed.ts` on real GitHub.
Four pre-seed feature branches exist on both sides before seeding. A merges
f1+f2 into `main`; B merges f3+f4 into `main`. Sync + shadow/main merge on
both sides → every feature's post-seed content ends up on both `main`s.
