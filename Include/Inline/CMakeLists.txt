set(PublicHeaders
	BasicTypes.h
	DenseStaticIntSet.h
	Errors.h
	Floats.h
	Serialization.h
	Timing.h
	Unicode.h)
add_custom_target(Inline SOURCES ${PublicHeaders})