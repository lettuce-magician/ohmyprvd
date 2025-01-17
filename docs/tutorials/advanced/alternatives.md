# Alternatives

Oh My Prvd is not the first Roblox game framework. In fact, there are several
existing game frameworks for Roblox. Besides Oh My Prvd, you might consider:

- [Knit by sleitnick](https://github.com/Sleitnick/Knit)
- [Flamework by fireboltofdeath](https://github.com/rbxts-flamework)
- [Nevermore by Quenty](https://github.com/Quenty/NevermoreEngine)
- [Proton by sleitnick](https://github.com/Sleitnick/rbxts-proton/)
- [Pronghorn by Iron Stag Games](https://github.com/Iron-Stag-Games/Pronghorn)
- [Lazy Modules by NightLapse Studios](https://github.com/NightLapse-Studios/LazyModules/)
- [Lumin Framework by Lumin Labs](https://github.com/lumin-dev/LuminFramework)

So, why did we make Oh My Prvd?

Each of these frameworks solve the same problem in multiple angles. The goal of
Oh My Prvd is to take all of the lessons and ideas learned from these projects
and build a framework that can solve this problem for good. In addition, all of
these frameworks have major drawbacks:

- Knit is under long term support with sparse updates and nearing an archive, in
  addition it introduces a hefty level of bloat, has subpar types;
- Flamework requires TypeScript and is tightly coupled with its transformer;
- Nevermore introduces an outrageous level of bloat and also harder to use,
  being geared primarily just for Quenty;
- Proton is under development and requires TypeScript;
- Pronghorn does not implement dependency injection, minimal extensibility and
  introduces some bloat;
- Lazy Modules has subpar syntax, somewhat couples code;
- Lumin Framework only focuses on networking and provides no primitives for
  singletons/providers;

Finally:

- We think a framework should be distributed as a single module, for decoupling
  and extensibility.
- We think a framework should be designed for both Luau and TypeScript.
- We think the conventions promoted by other frameworks (e.g. splitting between
  services and controllers, forcing games to follow a structure) are
  sub-optimal.
- We have a good enough understanding of the problem to develop something
  robust.
- We think Oh My Prvd should be able to do more than just connect providers.

This is not to say Oh My Prvd is superior, at least not yet:
