.PHONY: rule1 rule2 rule3

# Gán giá trị ngay (simple assignment)
var := "dcuong"
var3 := "var3"

# Gán theo nhiều cách khác nhau
var1 = $(var)         # Gán đệ quy: sẽ lấy giá trị hiện tại của `var` khi sử dụng
var2 := $(var)        # Gán ngay: lấy giá trị của `var` tại thời điểm này
var3 ?= $(var)        # Gán nếu chưa có giá trị (nhưng var3 đã có ở trên)

# Gán lại giá trị mới cho `var` để kiểm tra ảnh hưởng
var := "changed"

# Quy tắc in ra các biến
rule3:
	@echo "$(var1)"
	@echo "$(var2)"
	@echo "$(var3)"

# Quy tắc phụ đơn giản
rule1:
	echo "123"

rule2:
	@echo "123"

include a.mk
