licenses(["notice"])

cc_library(
    name = "g2o",
    srcs = [
        "g2o/core/batch_stats.cpp",
        "g2o/core/cache.cpp",
        "g2o/core/estimate_propagator.cpp",
        "g2o/core/factory.cpp",
        "g2o/core/hyper_dijkstra.cpp",
        "g2o/core/hyper_graph.cpp",
        "g2o/core/hyper_graph_action.cpp",
        "g2o/core/jacobian_workspace.cpp",
        "g2o/core/marginal_covariance_cholesky.cpp",
        "g2o/core/matrix_structure.cpp",
        "g2o/core/optimizable_graph.cpp",
        "g2o/core/optimization_algorithm.cpp",
        "g2o/core/optimization_algorithm_dogleg.cpp",
        "g2o/core/optimization_algorithm_factory.cpp",
        "g2o/core/optimization_algorithm_gauss_newton.cpp",
        "g2o/core/optimization_algorithm_levenberg.cpp",
        "g2o/core/optimization_algorithm_with_hessian.cpp",
        "g2o/core/parameter.cpp",
        "g2o/core/parameter_container.cpp",
        "g2o/core/robust_kernel.cpp",
        "g2o/core/robust_kernel_factory.cpp",
        "g2o/core/robust_kernel_impl.cpp",
        "g2o/core/solver.cpp",
        "g2o/core/sparse_block_matrix_test.cpp",
        "g2o/core/sparse_optimizer.cpp",
        "g2o/stuff/property.cpp",
        "g2o/stuff/string_tools.cpp",
        "g2o/stuff/timeutil.cpp",
        "g2o/types/sba/edge_project_p2mc.cpp",
        "g2o/types/sba/edge_project_p2sc.cpp",
        "g2o/types/sba/edge_project_psi2uv.cpp",
        "g2o/types/sba/edge_project_stereo_xyz.cpp",
        "g2o/types/sba/edge_project_stereo_xyz_onlypose.cpp",
        "g2o/types/sba/edge_project_xyz.cpp",
        "g2o/types/sba/edge_project_xyz2uv.cpp",
        "g2o/types/sba/edge_project_xyz2uvu.cpp",
        "g2o/types/sba/edge_project_xyz_onlypose.cpp",
        "g2o/types/sba/edge_sba_cam.cpp",
        "g2o/types/sba/edge_sba_scale.cpp",
        "g2o/types/sba/edge_se3_expmap.cpp",
        "g2o/types/sba/parameter_cameraparameters.cpp",
        "g2o/types/sba/sbacam.cpp",
        "g2o/types/sba/types_sba.cpp",
        "g2o/types/sba/types_six_dof_expmap.cpp",
        "g2o/types/sba/vertex_cam.cpp",
        "g2o/types/sba/vertex_intrinsics.cpp",
        "g2o/types/sba/vertex_se3_expmap.cpp",
        "g2o/types/sim3/types_seven_dof_expmap.cpp",
        "g2o/types/slam3d/dquat2mat.cpp",
        "g2o/types/slam3d/edge_se3.cpp",
        "g2o/types/slam3d/isometry3d_gradients.cpp",
        "g2o/types/slam3d/isometry3d_mappings.cpp",
        "g2o/types/slam3d/vertex_pointxyz.cpp",
        "g2o/types/slam3d/vertex_se3.cpp",
        "g2o/types/slam2d/vertex_point_xy.cpp",
        "g2o/types/slam2d/vertex_se2.cpp",
        "g2o/stuff/sparse_helper.cpp",
        "unit_test/general/base_fixed_sized_edge.cpp",
    ],
    hdrs = [
        "g2o/config.h",
        "g2o/core/base_binary_edge.h",
        "g2o/core/base_binary_edge.hpp",
        "g2o/core/base_edge.h",
        "g2o/core/base_fixed_sized_edge.h",
        "g2o/core/base_fixed_sized_edge.hpp",
        "g2o/core/base_multi_edge.h",
        "g2o/core/base_multi_edge.hpp",
        "g2o/core/base_unary_edge.h",
        "g2o/core/base_unary_edge.hpp",
        "g2o/core/base_variable_sized_edge.h",
        "g2o/core/base_variable_sized_edge.hpp",
        "g2o/core/base_vertex.h",
        "g2o/core/base_vertex.hpp",
        "g2o/core/batch_stats.h",
        "g2o/core/block_solver.h",
        "g2o/core/block_solver.hpp",
        "g2o/core/cache.h",
        "g2o/core/creators.h",
        "g2o/core/dynamic_aligned_buffer.hpp",
        "g2o/core/eigen_types.h",
        "g2o/core/estimate_propagator.h",
        "g2o/core/factory.h",
        "g2o/core/g2o_core_api.h",
        "g2o/core/hyper_dijkstra.h",
        "g2o/core/hyper_graph.h",
        "g2o/core/hyper_graph_action.h",
        "g2o/core/io_helper.h",
        "g2o/core/jacobian_workspace.h",
        "g2o/core/linear_solver.h",
        "g2o/core/marginal_covariance_cholesky.h",
        "g2o/core/matrix_operations.h",
        "g2o/core/matrix_structure.h",
        "g2o/core/openmp_mutex.h",
        "g2o/core/optimizable_graph.h",
        "g2o/core/optimization_algorithm.h",
        "g2o/core/optimization_algorithm_dogleg.h",
        "g2o/core/optimization_algorithm_factory.h",
        "g2o/core/optimization_algorithm_gauss_newton.h",
        "g2o/core/optimization_algorithm_levenberg.h",
        "g2o/core/optimization_algorithm_property.h",
        "g2o/core/optimization_algorithm_with_hessian.h",
        "g2o/core/ownership.h",
        "g2o/core/parameter.h",
        "g2o/core/parameter_container.h",
        "g2o/core/robust_kernel.h",
        "g2o/core/robust_kernel_factory.h",
        "g2o/core/robust_kernel_impl.h",
        "g2o/core/solver.h",
        "g2o/core/sparse_block_matrix.h",
        "g2o/core/sparse_block_matrix.hpp",
        "g2o/core/sparse_block_matrix_ccs.h",
        "g2o/core/sparse_block_matrix_diagonal.h",
        "g2o/core/sparse_optimizer.h",
        "g2o/custom/binary.h",
        "g2o/custom/extrinsics.h",
        "g2o/custom/unary.h",
        "g2o/EXTERNAL/ceres/fixed_array.h",
        "g2o/EXTERNAL/ceres/memory.h",
        "g2o/solvers/dense/linear_solver_dense.h",
        "g2o/solvers/eigen/linear_solver_eigen.h",
        "g2o/stuff/color_macros.h",
        "g2o/stuff/g2o_stuff_api.h",
        "g2o/stuff/macros.h",
        "g2o/stuff/misc.h",
        "g2o/stuff/os_specific.h",
        "g2o/stuff/property.h",
        "g2o/stuff/string_tools.h",
        "g2o/stuff/sampler.h",
        "g2o/stuff/sparse_helper.h",
        "g2o/stuff/timeutil.h",
        "g2o/stuff/tuple_tools.h",
        "g2o/types/sba/edge_project_p2mc.h",
        "g2o/types/sba/edge_project_p2sc.h",
        "g2o/types/sba/edge_project_psi2uv.h",
        "g2o/types/sba/edge_project_stereo_xyz.h",
        "g2o/types/sba/edge_project_stereo_xyz_onlypose.h",
        "g2o/types/sba/edge_project_xyz.h",
        "g2o/types/sba/edge_project_xyz2uv.h",
        "g2o/types/sba/edge_project_xyz2uvu.h",
        "g2o/types/sba/edge_project_xyz_onlypose.h",
        "g2o/types/sba/edge_sba_cam.h",
        "g2o/types/sba/edge_sba_scale.h",
        "g2o/types/sba/edge_se3_expmap.h",
        "g2o/types/sba/g2o_types_sba_api.h",
        "g2o/types/sba/parameter_cameraparameters.h",
        "g2o/types/sba/sbacam.h",
        "g2o/types/sba/sba_utils.h",
        "g2o/types/sba/types_sba.h",
        "g2o/types/sba/types_six_dof_expmap.h",
        "g2o/types/sba/vertex_cam.h",
        "g2o/types/sba/vertex_intrinsics.h",
        "g2o/types/sba/vertex_se3_expmap.h",
        "g2o/types/sim3/sim3.h",
        "g2o/types/sim3/types_seven_dof_expmap.h",
        "g2o/types/slam3d/dquat2mat.cpp",
        "g2o/types/slam3d/dquat2mat.h",
        "g2o/types/slam3d/dquat2mat_maxima_generated.cpp",
        "g2o/types/slam3d/edge_se3.h",
        "g2o/types/slam3d/g2o_types_slam3d_api.h",
        "g2o/types/slam3d/isometry3d_gradients.h",
        "g2o/types/slam3d/isometry3d_mappings.h",
        "g2o/types/slam3d/se3_ops.h",
        "g2o/types/slam3d/se3_ops.hpp",
        "g2o/types/slam3d/se3quat.h",
        "g2o/types/slam3d/vertex_pointxyz.h",
        "g2o/types/slam3d/vertex_se3.h",
        "g2o/types/slam2d/vertex_point_xy.h",
        "g2o/types/slam2d/vertex_se2.h",
        "g2o/types/slam2d/se2.h",
        "g2o/types/slam2d/g2o_types_slam2d_api.h",
    ],
    includes = [
        "./",
        "g2o",
        "g2o/core/",
        "g2o/custom/",
        "g2o/stuff/",
        "g2o/solvers/",
        "g2o/solvers/cholmod",
        "g2o/solvers/csparse",
        "g2o/solvers/dense",
        "g2o/solvers/eigen",
        "g2o/solvers/pcg",
        "g2o/solvers/slam2d_linear",
        "g2o/solvers/structure_only",
        "g2o/types/",
        "g2o/types/slam3d/",
        "g2o/types/slam2d/",
        "g2o/types/data/",
        "g2o/types/icp/",
        "g2o/types/sba/",
        "g2o/types/sclam2d/",
        "g2o/types/sim3/",
        "g2o/types/slam2d_addons/",
        "g2o/types/slam3d_addons/",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "@eigen",
    ],
    copts = ["-std=c++17"],
)