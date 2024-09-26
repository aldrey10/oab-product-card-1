# OAB-PRODUCT-CARD

Esto es un paquete de prueba de despliegue en npm

## Óscar Aldrey

### Esto es un ejemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from oab-product-card-1
```

```
<ProductCard
            product={product}
            initialValues={{
              count: 4,
              maxCount: 10
            }}
          >
            {
              ({reset, increaseBy, count, isMaxCountReached, maxCount}) => (
                <>
                  <ProductImage/>
                  <ProductTitle/>
                  <ProductButtons/>
                </>
              )
            }
        </ProductCard>

```