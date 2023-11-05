# Transformation

In RxJS, "transformation" refers to the process of modifying or manipulating the data emitted by an Observable. There are a variety of methods available in RxJS that can be used to transform the data emitted by an Observable, including:

- map: applies a function to each item emitted by the Observable and emits the resulting value
- flatMap: applies a function to each item emitted by the Observable, and then flattens the resulting Observables into a single Observable
- concatMap: applies a function to each item emitted by the Observable, and then concatenates the resulting Observables into a single Observable
- mergeMap: applies a function to each item emitted by the Observable, and then merges the resulting Observables into a single Observable
- switchMap: applies a function to each item emitted by the Observable, and then switches to the latest resulting Observable

These are just a few examples of the many methods available in RxJS for transforming the data emitted by an Observable. Each method has its own specific use case, and the best method to use will depend on the requirements of your application.

Here are the official documentation links for the RxJS transformation methods:

- [map](https://rxjs.dev/api/operators/map)
- [flatMap](https://rxjs.dev/api/operators/flatMap)
- [concatMap](https://rxjs.dev/api/operators/concatMap)
- [mergeMap](https://rxjs.dev/api/operators/mergeMap)
- [switchMap](https://rxjs.dev/api/operators/switchMap)

You can find more information and examples on these methods in the official RxJS documentation. Additionally, you can find more operators on https://rxjs.dev/api/operators and you can also find more information on the library as a whole on https://rxjs.dev/
