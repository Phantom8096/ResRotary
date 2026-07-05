/// <summary>
/// res rotary table for industrial manipulator
/// </summary>
/// <param name="rot_table">Pose of Center of Rotary Table</param>
/// <param name="param">[6]Desired Point in Rotary</param>
/// <param name="n">length of point list</param>
/// <param name="point_list">[nx6]Points in Rotary</param>
/// <param name="robot_list">[nx6]Points in Robot</param>
/// <param name="table_list">[n]Joints of Rorary</param>
/// <returns></returns>
__declspec(dllexport) int res_rotary(const double rot_table[6], const double* param, int n, const double* point_list, double* robot_list, double* table_list);
