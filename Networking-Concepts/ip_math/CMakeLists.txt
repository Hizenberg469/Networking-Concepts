set(IPMATH_SRC "ip_math.c")

set(IPMATH_EXE "ipMath")

add_executable(${IPMATH_EXE}
				${IPMATH_SRC})


#Linking library
set(MATH_LIB m)

target_link_libraries(${IPMATH_EXE} PUBLIC
						${MATH_LIB})