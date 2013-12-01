njjkjlkj
========
var tumblr = require('tumblr.js');
var client = tumblr.createClient({artisticallycapricious})
  consumer_key: '<YhMlOcF4lha9cdcl2MC75RqzwAKtGupSavP6kgWf6SVlJSkRBv>',
  consumer_secret: '<B9KM7HXwSbKYBTjgUD2CQkn5sq0tE7a8fHpOJHE6WKgBVEknZX>',
  token: '< kebBS9HIoV61E8I5xcjXURimik2BXnCxsWnHItZhnmvX05zq5j>',
  token_secret: '<gLOJ0U9CcLi94Oqk062KI2p5WIymdHxbbXFB4dddSdDkkkV8AY>'
});
client.userInfo(callback);

client.dashboard(options, callback);
client.dashboard(callback);

client.likes(options, callback);
client.likes(callback);

client.following(options, callback);
client.following(callback);

client.follow(blogURL, callback);
client.unfollow(blogURL, callback);

client.like(id, reblogKey, callback);
client.unlike(id, reblogKey, callback);
