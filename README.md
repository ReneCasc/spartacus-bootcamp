# spartacus-bootcamp

Training URL - https://api.ccm7g9h-meesandbo1-d14-public.model-t.cc.commerce.ondemand.com/

Schematics command - ng add @spartacus/schematics --baseUrl https://api.ccm7g9h-meesandbo1-d14-public.model-t.cc.commerce.ondemand.com --baseSite electronics-spa

Spartacus source - https://github.com/SAP/spartacus

Missing Product Search Lines:

ConfigModule.withConfig({
      backend: {
        occ: {
          endpoints: {
      productSearch:
      'products/search?fields=products(code,manufacturer,name,summary,price(FULL),images(DEFAULT),stock(FULL),averageRating,variantOptions),facets,breadcrumbs,pagination(DEFAULT),sorts(DEFAULT),freeTextSearch,currentQuery',
          }
        }
      }
    } as OccConfig),
