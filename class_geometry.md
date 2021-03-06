#  Geometry  
####**Inherits:** [Object](class_object)
####**Category:** Core

###  Brief Description  


###  Member Functions 
  * [Array](class_array)  **[build&#95;box&#95;planes](#build_box_planes)**  **(** [Vector3](class_vector3) extents  **)**
  * [Array](class_array)  **[build&#95;cylinder&#95;planes](#build_cylinder_planes)**  **(** [float](class_float) radius, [float](class_float) height, [int](class_int) sides, [int](class_int) axis=2  **)**
  * [Array](class_array)  **[build&#95;capsule&#95;planes](#build_capsule_planes)**  **(** [float](class_float) radius, [float](class_float) height, [int](class_int) sides, [int](class_int) lats, [int](class_int) axis=2  **)**
  * [float](class_float)  **[segment&#95;intersects&#95;circle](#segment_intersects_circle)**  **(** [Vector2](class_vector2) segment_from, [Vector2](class_vector2) segment_to, [Vector2](class_vector2) circle_pos, [float](class_float) circle_radius  **)**
  * void  **[segment&#95;intersects&#95;segment&#95;2d](#segment_intersects_segment_2d)**  **(** [Vector2](class_vector2) from_a, [Vector2](class_vector2) to_a, [Vector2](class_vector2) from_b, [Vector2](class_vector2) to_b  **)**
  * [Vector2Array](class_vector2array)  **[get&#95;closest&#95;points&#95;between&#95;segments&#95;2d](#get_closest_points_between_segments_2d)**  **(** [Vector2](class_vector2) p1, [Vector2](class_vector2) q1, [Vector2](class_vector2) p2, [Vector2](class_vector2) q2  **)**
  * [Vector3Array](class_vector3array)  **[get&#95;closest&#95;points&#95;between&#95;segments](#get_closest_points_between_segments)**  **(** [Vector3](class_vector3) p1, [Vector3](class_vector3) p2, [Vector3](class_vector3) q1, [Vector3](class_vector3) q2  **)**
  * [Vector3](class_vector3)  **[get&#95;closest&#95;point&#95;to&#95;segment](#get_closest_point_to_segment)**  **(** [Vector3](class_vector3) point, [Vector3](class_vector3) s1, [Vector3](class_vector3) s2  **)**
  * [int](class_int)  **[get&#95;uv84&#95;normal&#95;bit](#get_uv84_normal_bit)**  **(** [Vector3](class_vector3) normal  **)**
  * void  **[ray&#95;intersects&#95;triangle](#ray_intersects_triangle)**  **(** [Vector3](class_vector3) from, [Vector3](class_vector3) dir, [Vector3](class_vector3) a, [Vector3](class_vector3) b, [Vector3](class_vector3) c  **)**
  * void  **[segment&#95;intersects&#95;triangle](#segment_intersects_triangle)**  **(** [Vector3](class_vector3) from, [Vector3](class_vector3) to, [Vector3](class_vector3) a, [Vector3](class_vector3) b, [Vector3](class_vector3) c  **)**
  * [Vector3Array](class_vector3array)  **[segment&#95;intersects&#95;sphere](#segment_intersects_sphere)**  **(** [Vector3](class_vector3) from, [Vector3](class_vector3) to, [Vector3](class_vector3) spos, [float](class_float) sradius  **)**
  * [Vector3Array](class_vector3array)  **[segment&#95;intersects&#95;cylinder](#segment_intersects_cylinder)**  **(** [Vector3](class_vector3) from, [Vector3](class_vector3) to, [float](class_float) height, [float](class_float) radius  **)**
  * [Vector3Array](class_vector3array)  **[segment&#95;intersects&#95;convex](#segment_intersects_convex)**  **(** [Vector3](class_vector3) from, [Vector3](class_vector3) to, [Array](class_array) planes  **)**
  * [IntArray](class_intarray)  **[triangulate&#95;polygon](#triangulate_polygon)**  **(** [Vector2Array](class_vector2array) polygon  **)**
  * [Dictionary](class_dictionary)  **[make&#95;atlas](#make_atlas)**  **(** [Vector2Array](class_vector2array) sizes  **)**

###  Member Function Description  
