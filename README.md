# NewshoreClient

This project is the client side of the Newshore assessment, it was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.2.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.
The API side will allow request from `http://localhost:4200/` plase keep the suggested port to avoid CORS error from the API.

## Development server using a custom proxy

Run `npm run start:proxy` to set the initial configuration based on the proxy configuration, this will modify the origin request to make it the same as the API source, avoiding CORS error, however the API already accept request from `http://localhost:4200/` this is only necesary in case of changing that configuration in the API.


### note:
The feature to change the currency is working according to the "normal" conversion, meaning that due to the used conversion values, a small precision will be lost, causing a constant reduction or increase in the original value, i.e. changing the currency from USD to COP and return back to USD, will cause a mismatch based in the inital amount, however, this is an 'allowed' behavior, can be checked performing the same exercise here: [google.com/finance/USD-COP](https://www.google.com/finance/quote/USD-COP?sa=X&ved=2ahUKEwik5vq6k4-AAxXjTTABHWKuBzIQmY0JegQIBhAc)

The Currency feature is reling on an [external API](https://exchangerate.host/#/donate) to enhance its functionality. Please be informed that the credits, rights, and ownership of the API content belong solely to their respective owners. While every effort is made to ensure seamless integration and reliable performance, it is important to acknowledge that any failures, disruptions, or inaccuracies encountered with the API's functionality are beyond my control and I cannot be held responsible for such occurrences. 


![image](https://github.com/PipeSierra/Newshore.client/assets/29931193/d9835344-2276-4e7f-90d5-c34c11cd06e5)
