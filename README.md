# APN-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Alberto Pimentel

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'apn-product-card';
```

```
 <ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({ reset, isMaxCountReached, count, increaseBy, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```
