# hass-destiny

```yaml
- platform: destiny2
  membership_type: 2
  destiny_membership_id: 4611686018428481758
  api_key: !secret destiny2_api_key
```

Finding your `membership_type` and `destiny_membership_id` can be done by navigating to your profile on the Bungie website then clicking on the platform you're interested in (e.g. `PlayStation Network`).Your `membership_type` will the first number after `profile` in the url and your `destiny_membership_id` is the second number.

```
e.g.
My profile is [https://www.bungie.net/en/Profile/**2**/**4611686018428481758**/Atraignis](https://www.bungie.net/en/Profile/2/4611686018428481758/Atraignis)
So my details are:
  membership_type: 2
  destiny_membership_id: 4611686018428481758
```

To get your API key you need to sign up at [Bungie's Application Portal](https://www.bungie.net/en/Application) and create an application.
