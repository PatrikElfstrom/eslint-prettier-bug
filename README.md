# eslint-prettier-bug

Run `npm run lint` to lint the `index.ts` file

The linting should (if the error occurs) produce a file looking like this.
Notice the extra curly bracket.

```
export default class MyClass {
    myMethod() {
        return {
            callbacks: {
                label: () => {
                        if (true) {
                            if (true) {
                                return '';
                            }
                            if (true) {
                                return '';
                            }
                        }
                    }
                }
            }
        };
    }
}

```
