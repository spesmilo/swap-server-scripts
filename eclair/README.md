Eclair management tools

Examples:

 $ ./init_db
 $ ./channels --public --sortby nodeId  | ./format
 $ ./channels --private --sortby toLocal | ./format
 $ ./channels | ./sum_balances
 $ ./relayed_by_channel 718327x534x2
 $ eclair peers | ./connected | jq -s 'length'
