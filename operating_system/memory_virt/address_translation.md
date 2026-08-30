+ [Virtual address](/operating_system/memory_virt/virtual_address.md)
+ [Physical address](/operating_system/memory_virt/virtual_address.md)
+ [Memory management unit](/hardware/chips/memory_management_unit.md)

## Address translation

Address translation is the process of converting a process **virtual address**
into its **physical address**. The address translation process depends entirely
on the way memory is managed within processes, but in general can be classified
into two different categories

+ Static translation
+ Dynamic translation

Static translation converts all virtual addresses into physical addresses before
running the process so it cannot be changed later. Dynamic translation allow to
change physical address at runtime by tuning certain process parameters and the
translation is done at the **memory management unit**

