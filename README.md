# QuantityView
# 带有增加与减少按钮的数量选择控件

https://github.com/himanshu-soni/QuantityView

![Old Menu Buttons](https://github.com/836948082/BoomMenu/blob/master/image/old_action_bar_menu.png)

<com.runtai.quantityviewlibrary.QuantityView
    android:id="@+id/quantityView_custom_1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_marginTop="10dp"
    app:qv_addButtonText="ADD MORE"                             //设置增加的文字
    app:qv_addButtonTextColor="@color/md_green_500"             //设置增加的文字颜色(Color)
    app:qv_addButtonBackground="@drawable/add_selector"         //设置增加的背景
    app:qv_maxQuantity="20"                                     //设置最大数量
    app:qv_minQuantity="2"                                      //设置最小数量
    app:qv_quantity="15"                                        //设置数量
    app:qv_quantityDialog="false"                               //设置点击数量是否可弹出编辑框(Dialog)
    app:qv_removeButtonText="REMOVE"                            //设置减少的文字
    app:qv_removeButtonTextColor="@color/md_red_500"            //设置减少的文字颜色(Color)
    app:qv_removeButtonBackground="@drawable/remove_selector" />//设置减少的背景