
# Yoast to REST API - WordPress plugin

For use with the new [WP REST API](http://v2.wp-api.org/)

Returns Yoast post or page metadata in a normal post or page request. Stores the metadata in the `yoast_meta` field of the returned data.

```
{
  id: 123,
  ...
  seo_meta: {
    seo_title: "Testy Test | My WordPress site",
    seo_metadesc: "My description",
    seo_canonical: "http://my-wordpress-site.test/testy-test"
  }
}
```

Supports pages, posts, categories, tags and any *public* custom post types

Currently fetching:

- `yoast_wpseo_title`
- `yoast_wpseo_metadesc`
- `yoast_wpseo_canonical`

Currently updating:

- `yoast_wpseo_focuskw`
- `yoast_wpseo_title`
- `yoast_wpseo_metadesc`
- `yoast_wpseo_linkdex`
- `yoast_wpseo_metakeywords`
- `yoast_wpseo_meta-robots-noindex`
- `yoast_wpseo_meta-robots-nofollow`
- `yoast_wpseo_meta-robots-adv`
- `yoast_wpseo_canonical`
- `yoast_wpseo_redirect`
- `yoast_wpseo_opengraph-title`
- `yoast_wpseo_opengraph-description`
- `yoast_wpseo_opengraph-image`
- `yoast_wpseo_twitter-title`
- `yoast_wpseo_twitter-description`
- `yoast_wpseo_twitter-image`

Thanks to Pablo Postigo, Tedy Warsitha and Charlie Francis for amazing contributions!
