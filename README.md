###UPDATE wety.tema,dictionary
SET user.password=dictionary.word
WHERE user.pass_md5=dictionary.md5
