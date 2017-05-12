# recyclerViewDivider
recyclerView 分割线

recyclerView

 分割线添加默认分割线  灰色 2px 
 
 mRecyclerView.addItemDecoration(new RecyclerViewDivider(mContext, LinearLayoutManager.VERTICAL));
 
  添加自定义分割线：可自定义分割线drawable
  
 mRecyclerView.addItemDecoration(new RecyclerViewDivider(
    mContext, LinearLayoutManager.VERTICAL, R.drawable.divider_mileage));
    
 添加自定义分割线：可自定义分割线高度和颜色
 
   mRecyclerView.addItemDecoration(new RecyclerViewDivider(
      mContext, LinearLayoutManager.VERTICAL, 10, ContextCompat.getColor(mContext, R.color.divide_gray_color)));
