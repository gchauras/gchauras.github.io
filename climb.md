---
layout: page
permalink: /misc/climbing.html
title: Climbing
gyms:

  - name:         "MIT gym"
    gym_url:      "http://scripts.mit.edu/~mitoc/wall/about/"
    location:     "MIT Campus, Walker Memorial Room 303"
    location_url: "https://www.google.com/maps/place/Walker+Memorial,+Massachusetts+Institute+of+Technology,+Cambridge,+MA+02142/@42.3593663,-71.0883214,17z/data=!3m1!4b1!4m2!3m1!1s0x89e370a852ddb747:0xacbd55c556ae6f92"
    day_pass:     "free"
    rentals:      "shoes $1"

  - name:         "Rock Spot South Boston (coming up)"
    gym_url:      "http://www.rockspotclimbing.com/"
    location:     "30 Old Colony Ave, Boston, MA 0212"
    location_url: "https://www.google.com/maps/place/30+Old+Colony+Ave,+Boston,+MA+02127/@42.336952,-71.0563264,17z/data=!4m2!3m1!1s0x89e37a66a5cacba5:0x792777cff091536e"
    day_pass:     "$16, $70, $130; $220 (for 1, 5, 10 and 20 days)"
    rentals:      "shoes $5, harness $3, $8 full gear (special prices for multi-day passes)"

  - name:         "Rock Spot "
    gym_url:      "http://www.rockspotclimbing.com/"
    location:     "67 Sprague St, Boston, MA 02136"
    location_url: "https://www.google.com/maps/place/Rock+Spot+Climbing/@42.234964,-71.138213,17z/data=!3m1!4b1!4m2!3m1!1s0x89e37e4976206a51:0x38ac7f3627969a33"
    day_pass:     "$16, $70, $130; $220 (for 1, 5, 10 and 20 days)"
    rentals:      "shoes $5, harness $3, $8 full gear (special prices for multi-day passes)"

  - name:         "Boston Rock"
    gym_url:      "http://www.bostonrockgym.com/"
    location:     "78G Olympia Ave, Woburn, MA 01801"
    location_url: "https://www.google.com/maps/preview?ll=42.498862,-71.138392&z=16&t=m&hl=en-GB&gl=US&mapclient=embed&cid=17985961633952160380"
    day_pass:     "adult $16, student $14; adult $96, student $84 (7 visits)"
    rentals:      "shoes $4, harness $2"

  - name:         "Metro Rock Everett"
    gym_url:      "http://www.metrorock.com/boston"
    location:     "69 Norman Street, Everett, MA 02149"
    location_url: "https://www.google.com/maps/place/MetroRock+Climbing+Center/@42.408019,-71.0666235,17z/data=!4m5!1m2!2m1!1s69+Norman+Street+%E2%80%A2+Everett,+MA+%E2%80%A2+02149!3m1!1s0x0:0x86658f5a7f34b222"
    day_pass:     "adult $20, student $16; adult $180, student $144 (10 visits)"
    rentals:      "shoes $5, harness $3"

  - name:         "Brooklyn Boulders Somerville"
    gym_url:      "http://bkbs.brooklynboulders.com/"
    location:     "12a Tyler Street, Somerville"
    location_url: "https://www.google.com/maps/place/Brooklyn+Boulders/@42.381727,-71.105905,17z/data=!3m1!4b1!4m2!3m1!1s0x89e377365810bec3:0xfe4e83648f71541a"
    day_pass:     "adult $22, student $18; adult $199, student $156 (10 visits)"
    rentals:      "shoes $5, harness $5"

  - name:         "Central Rock Watertown"
    gym_url:      "http://www.centralrockgym.com/watertown.php"
    location:     "74 Acton St, Watertown, MA 02472"
    location_url: "https://www.google.com/maps/place/Central+Rock+Gym/@42.369399,-71.198529,17z/data=!3m1!4b1!4m2!3m1!1s0x89e382aed38360bb:0x6c59748670876824"
    day_pass:     "adult $20, student $16"
    rentals:      "shoes $5, harness $5"

  - name:         "Central Rock Worcester"
    gym_url:      "http://www.centralrockgym.com/worcester.php"
    location:     "299 Barber Ave, Worcester, MA 01606"
    location_url: "https://www.google.com/maps/place/Central+Rock+Gym/@42.296841,-71.797531,17z/data=!3m1!4b1!4m2!3m1!1s0x89e407bacdf18b41:0xe04912a5aee3eb77"
    day_pass:     "adult $16, student $12"
    rentals:      "shoes $5, harness $5"

  - name:         "Central Rock Hadley"
    gym_url:      "http://www.centralrockgym.com/hadley.php"
    location:     "165 Russel St, Hadley, MA 01035"
    location_url: "https://www.google.com/maps/place/Central+Rock+Gym/@42.342169,-72.584597,17z/data=!3m1!4b1!4m2!3m1!1s0x89e6d11a321865c1:0x24134bc7f36a19ee"
    day_pass:     "adult $16, student $12"
    rentals:      "shoes $5, harness $5"

  - name:         "Carabiners"
    gym_url:      "http://carabiners.com/new-bedford/"
    location:     "328 Parker Street, New Bedford"
    location_url: "https://www.google.com/maps/place/328+Parker+St,+New+Bedford,+MA+02740/@41.642126,-70.9480449,17z/data=!3m1!4b1!4m2!3m1!1s0x89e4e386d0bd2021:0xb5fe8715e2fab6cc"
    day_pass:     "adult $16, student $10"
    rentals:      "none"

---

Some climbing places in and around Boston.

{% for gym in page.gyms %}
- [{{gym.name}}]({{gym.gym_url}}) <br />
  {{gym.location}} [[Map]({{gym.location_url}})] <br />
  Day pass: {{gym.day_pass}} <br />
  Rentals: {{gym.rentals}}
{% endfor %}

