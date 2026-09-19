SouthCoast Eats V2 Consumer — 3 fixes
=====================================

This ZIP contains the replacement index.html for the SouthCoast Eats consumer app.

Included fixes:
1. American food tile replaced with Portuguese.
2. Asian tile recognizes V2-specific Asian cuisines such as Chinese, Korean, Thai, Japanese, Vietnamese, Indonesian, and Filipino.
3. Drive-Thru service was added and is driven by V2 is_drive_through_available=true.

The app reads from the V2 Supabase consumer_restaurants_v2 view.

Upload/replace index.html in:
jrouellette/southcoast-eats-app

The existing brand-logo.jpg and coastal-footer.jpg remain referenced from the repository.
