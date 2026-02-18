# Hi! 👋 I'm Petter 🙋‍♂️

```typescript
export type Petter<SomethingExciting extends FullstackWork> = {
  pronouns: "he" | "him";
  ["twitter/x"]: "@pettersmoen";
  bluesky: "@pmoen.me";
  blog: "pmoen.me";
  basedIn: "Toronto 🇨🇦";

  workStatus: "Looking for new opporunities";
  currentlyLookingFor: SomethingExciting;
  interests: "Creating stuff" | "Golf" | "Running" | "AI" | (string & {});
};
```
