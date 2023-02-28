1. 프로젝트 설계

- 상태 데이터(할일)

[
{
uid: string(날짜),
title: string(제목),
body: string(내용),
done: boolean(수행여부),
sticker: string(이미지),
date: string(날짜)
}
]

2. 기능 정의
   추가 기능 - addTodo(title: string, body: string, date: string, sticker: string,
   sticker: string, done: boolean = false) void
   수정 기능 - updateTodo(todo: TodoType) void
   삭제 기능 - deleteTodo(todo: TodoType) void
