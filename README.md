# Hi! 👋 I'm Petter 🙋‍♂️

```typescript
export type Petter<SomethingExciting extends FullstackWork> = {
  pronouns: "he" | "him";
  ["twitter/x"]: "@pettersmoen";
  bluesky: "@pmoen.me";
  blog: "pmoen.me";

  employedAt: "Bekk";
  role: "Consultant";
  currentlyWorkingOn: SomethingExciting;
  interests: "Creating stuff" | "Golf" | "Gaming" | "Pizza" | (string & {});
};
```
