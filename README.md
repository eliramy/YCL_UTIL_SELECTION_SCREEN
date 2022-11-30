# YCL_UTIL_SELECTION_SCREEN

Selection Screen Util 

How to Use method GET_VARIANT_SALV in program:


PARAMETERS:
  p_var type slis_vari.

AT SELECTION-SCREEN ON VALUE-REQUEST FOR p_var.
  p_var = ycl_util_selection_screen=>get_variant_salv( iv_repid = sy-repid ).
