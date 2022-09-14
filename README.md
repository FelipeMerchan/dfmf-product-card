#DFMF-Product-Card

Este es un paquete de pruebas de despliegue en NPM.

### Felipe Merchan

## Ejemplo

```
import {
    ProductCard,
    ProductImage,
    ProductTitle,
    ProductButtons,
} from 'dfmf-product-card
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 6,
        maxCount: 10,
    }}
>
    {
        () => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```