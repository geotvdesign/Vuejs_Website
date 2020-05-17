<template>
  <div class="contact" id="contact">
    <div class="ttl mt-5 mb-5">contact</div>
    <form action="" method="" class="form-horizontal">
      <div class="form-group">
        <label class="col-sm-3 control-label" for="name1">お名前</label>
        <div class="col-sm-6">
          <input type="text" class="form-control" name="">
        </div>
      </div>
      <div class="form-group">
        <label class="col-sm-3 control-label" for="name">会社名・事業所名</label>
        <div class="col-sm-6">
          <input type="text" class="form-control" name="">
        </div>
      </div>
      <div class="form-group">
        <label class="col-sm-3 control-label" for="email">メールアドレス</label>
        <div class="col-sm-6">
          <input type="text" class="form-control" name="">
        </div>
      </div>
      <div class="form-group">
        <label class="col-sm-3 control-label" for="ask1">お問い合わせ内容</label>
        <div class="col-sm-6">
          <textarea rows="7" name="" class="form-control"></textarea>
        </div>
      </div>
      <div class="form-group">
        <label class="col-sm-3"></label>
        <div class="col-sm-8">
          <button class="btn btn-default mr-3">リセット</button>
          <button class="btn btn-default text-white bg-dark">送信する</button>
        </div>
      </div>
    </form>
  </div>
</template>

<style scoped>
  .contact {
    height: 1000px;
    background-color: #ffffff;
  }

  .form-horizontal {
    width: 50%;
    margin: 0 auto;
  }

  .form-group {
    display: flex;
  }

  .btn {
    border: solid 1px #555;
  }

</style>
