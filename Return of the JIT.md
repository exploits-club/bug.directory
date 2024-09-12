tags: #v8 #JIT #chrome
original link: [Return of the JIT](https://lampreylabs.com/posts/return-of-the-jit/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 30](https://blog.exploits.club/exploits-club-weekly-newsletter-30/)

---
## Exploits Club Summary:
> A short fun and short post from [@_winterknife_](https://x.com/_winterknife_?ref=blog.exploits.club) discussing **recent changes to the behavior of the V8 optimizer toggle in Chrome.** Previously, individuals were using this toggle as a means disabling JIT and switching V8 to interpreter-only mode. However, **since late June, the behavior of this toggle was changed to only disable the 2 higher tiers of JIT compilation, leaving** [**Sparkplug**](https://v8.dev/blog/sparkplug?ref=blog.exploits.club) **enabled.** The theory is this may have been introduced to not break WASM, but if its **something you're worried about, the blog offers a workaround using the `jitless` command-line flag.**