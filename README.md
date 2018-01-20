# SwipeRefreshLayout
Example

```java
        mSwipeRefreshLayout.setColorSchemeResources(R.color.holo_green_light,
                R.color.holo_blue_bright,
                R.color.holo_orange_light,
                R.color.holo_red_light);
        mSwipeRefreshLayout.setOnRefreshListener(new SwipeRefreshLayout.OnRefreshListener() {
            @Override
            public void onRefresh() {
                Toast.makeText(MainActivity.this, "No data entry!", Toast.LENGTH_SHORT).show();
                mSwipeRefreshLayout.setRefreshing(false);
            }
        });
```
