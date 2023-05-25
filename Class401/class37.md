What concerns are addressed by Redux Toolkit?
Redux Toolkit makes Redux easier to use by reducing the amount of code you need to write. It makes managing global state and creating actions simpler.

What does configureStore() do?
configureStore() sets up your Redux store with some default settings. It makes it easier to add middleware and to set up the Redux devtools.

How would I use createSlice()?
createSlice() helps you generate actions and reducers automatically. You just give it your initial state, your reducers, and a name. This means you write less code, because you don't need to write action types and creators by hand.

What is MobX?
MobX is a library for managing and synchronizing application state using observables, actions, and reactions.

How does MobX make it “impossible” to produce an inconsistent state?
MobX prevents inconsistent state by tracking changes to observables automatically and using actions to make atomic, deterministic changes to state.

How would we build a reactive user interface?
A reactive UI automatically updates when the state changes. With MobX, you make your state "observable" and your components automatically re-render when the state they depend on changes.

The Redux documentation offers tutorials for learning Redux and Redux Toolkit. The tutorials cover topics such as quick starts, essentials, fundamentals, modern Redux, using Redux Toolkit, TypeScript integration, and migrating from traditional Redux. They provide guidance on using Redux effectively, building real-world applications, understanding Redux concepts, and leveraging Redux Toolkit to simplify Redux development. The tutorials cater to beginners and those seeking a deeper understanding of Redux and its recommended patterns.
