# angular2-fractionize

[![npm version](https://badge.fury.io/js/angular2-fractionize.svg)](https://badge.fury.io/js/angular2-fractionize)

Angular Pipe that formats numbers to a fraction

## Install

```
npm install angular2-fractionize
```

## FractionizeModule

```ts
import { FractionizeModule } from 'angular2-fractionize';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    FractionizeModule
  ],
  bootstrap: [ AppComponent ],
})
export class AppModule {}
```

## FractionizePipe

```ts
@Component({
  // ...
})
class AppComponent() {
  x: string = `2.4`;
}
```

```html
<p> {{ description | fractionize }} </p>
```

Outputs: 2 &#x2156;

