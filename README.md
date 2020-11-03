## Presentation for Hacker Friday 6/11

### Testing

* [**MSW**](https://mswjs.io/)
* [**Testing-library**](https://testing-library.com/docs/react-testing-library/intro/)
* [**Jest**](https://jestjs.io/en/) ([`ts-jest`](https://github.com/kulshekhar/ts-jest) for typescript)

### Store solution

* [WebPlatform/`ReduceStore`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/stores/reduceStore.ts)
* [**Redux Toolkit**](https://redux-toolkit.js.org/)
* [WebPlatform/`useGetStore`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/hooks/useStore.ts)
* [WebPlatform/`connect`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/hocs/connect.tsx)
* [WebPlatform/`Provider`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/components/provider/provider.tsx)

### Helpers functions

* [`BaseCrudApi`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/modules/baseCrudApi.ts)
* [`createStore`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/framework/createStore.spec.ts)
* [`crudActions`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/actions/crudActions.ts)
* [`crudActionCreators`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/actionCreators/crudActionCreators.ts)
* [`createCrudMockServer`](https://github.com/Caspeco/WebPlatform/blob/dev/source/framework/createCrudMockServer.ts)

### Specs that are set up with these tools:

* [`createStore.spec.spec.ts`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/framework/createStore.spec.ts)
* [`createCrudActions.spec.ts`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/framework/createCrudActions.spec.ts)
* [`createCrudActionCreators.spec.ts`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/framework/createCrudActionCreators.spec.ts)
* [`baseCrudApi.spec.ts`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/framework/baseCrudApi.spec.ts)
* [`hackers.spec.tsx`](https://github.com/Caspeco/WebPlatform/blob/hf/tests/application/hackers.spec.tsx)
* [`userView.spec.tsx`](https://github.com/Caspeco/WebPlatform/blob/dev/tests/views/usersView.spec.tsx)