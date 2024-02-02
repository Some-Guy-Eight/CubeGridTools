# CubeGridTools

enum Corners
static class CornersExtensions

enum Direction
static class DirectionExtensions
static class DirectionHelper

enum DirectionTypes // [Flags]
static class DirectionTypesExtensions
static class DirectionTypesHelper

enum Directions // [Flags]
static class DirectionsExtensions
static class DirectionsHelper

enum PlanarRotations // [Flags]
static class PlanarRotationsExtensions

enum Planes // [Flags]
static class PlanesExtensions
static class PlanesHelper

class RelativeDirections
// > all directions relative to the ZY, XZ, or XY Planes
//   > covers all 26 'neighbor' cells in a cube grid
// > returns an instance with the relative right, up, fwd Directions

class RelativeVectors
// > all directions relative to the ZY, XZ, or XY Planes
//   > covers all 26 'neighbor' cells in a cube grid
// > returns an instance with the relative right, up, fwd Vector3

class RelativeVectorsInt
// > all Vecotr3 relative to the ZY, XZ, or XY Planes
//   > covers all 26 'neighbor' cells in a cube grid
// > returns an instance with the relative right, up, fwd Vector3Int
