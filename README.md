#   Angular PrimeNG


How to Install Angular PrimeNG
1.  Install the next libraries :
    npm install primeng --save
    npm install primeicons --save
    npm install @angular/animations --save


import {BrowserModule} from '@angular/platform-browser';
import {BrowserAnimationsModule} from '@angular/platform-browser/animations';

@NgModule({
    imports: [
        BrowserModule,
        BrowserAnimationsModule,
        //...
    ],
    //...
})
export class YourAppModule { }

2. https://unicode-table.com/es/223D/ style.scss

22-07-2022 No hay Soporte oficial para Angular V14 pero usando la siguiente instruccion
npm install primeng --save --legacy-peer-deps


