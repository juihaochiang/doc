## Schedule

### 3.17
#### 计划
探讨vCPU相关实现

#### 总结
学习并讨论VMX相关指令在手册查阅方式，确定未来将长期查阅和学习该手册(SDM-VOL-3C)

讨论了shoot4u原理和流程

无法确定哪些代码是和vcpu相关的，根据手册信息，从VMCS入手


### 3.24

#### 计划
学习手册中VMCS部分原理

结合代码，提交并讨论VMCS结构和相关所有接口的作用、实现原理，给出总结文档

#### 总结
讨论了VMCS的布局和字段。


### 3.31

#### 计划
学习并注释kvm_arch_vcpu_create、kvm_arch_vcpu_setup和kvm_arch_vcpu_postcreate函数。

#### 总结
注释完毕


### 4.7 + 4.14
时钟相关。

@tcbbd tsc
@binss kvmclock
@chrisbyd pit

### 4.21
@tcbbd tsc，生命周期
@binss 动态迁移
@chrisbyd 中断，中断注入
