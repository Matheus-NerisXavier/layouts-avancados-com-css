# Flex shorthand

initial -> 0 1 auto
auto -> 1 1 auto
none -> 0 0 auto
um valor -> {
  se númerico -> grow -> <grow> 1 0 
  se unit -> basis -> 1 1 <basis>
}

dois valores -> {
  grow | [shrink | basis]
  se numérico -> shrink <grow><shrink> 0
  se unit -> basis -> <grow> 1 <basis>
}

tres valores -> {
  grow shrink basis -> a ordem importa!
}