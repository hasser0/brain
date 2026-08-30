## Free list

Free list is an OS data structure that allow to track memory chunks not
allocated to any process

Usually the free list is managed along with the memory managed, so that before
any memory chunk there is a header structure that defines so metadata to manage
free spaces. This header structure include memory size, next free space and
other chunk properties.

