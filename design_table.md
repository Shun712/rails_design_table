- users
  - id: integer
  - name: string
  - email: string
  - password_digest: string
  - nickname: string
  - picture: string
  - admin: boolean

- questions
  - id: integer
  - user_id: integer
  - title: string
  - content: text
  - solved_check: integer

- notifications
  - id: integer
  - question_id: integer
  - user_id: integer