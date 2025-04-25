.banner-container {
    min-height: 100px;
    display: flex;
    flex-direction: column;
    padding-top: 30px;
    background-color: rgb(246, 247, 251);
    margin-bottom: 20px;
    padding-bottom: 30px;
}

.banner-main-section {
    display: flex;
    align-items: center;
    min-height: 60px;
    justify-content: space-between;
}

.banner-left-section > li {
    display: flex;
    flex-direction: column;
    width: 100%;
    gap: 10px;
    font-size: 28px;
    font-weight: 600;
}

.banner-left-section > span:first-child {
    line-height: 100%;
    color: #4D4D4D;
}

.banner-left-section > #span-sub-text {
    line-height: 100%;
    color: rgb(74, 176, 77);
}

.banner-left-section > small {
    font-weight: 400;
    font-size: 16px;
    color: #717171;
    line-height: 150%;
}

.banner-left-section > span:first-child,
.banner-left-section > #span-sub-text,
.banner-left-section > small {
    text-align: center;
}

.banner-illustration {
    width: 38%;
    height: auto;
    display: none;
    justify-content: flex-end;
}

.banner-illustration>img {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain;
    object-position: center;
}

.button-element {
    outline-style: none;
    border: 0;
    border: 2px solid rgb(74, 176, 77);
    background-color: rgb(74, 176, 77);
    color: #fff;
    font-weight: 500;
    font-size: 16px;
    width: 120px;
    height: 37px;
    border-radius: 3px;
    cursor: pointer;
    margin: auto;
}


.pixelgrade-section {
  border: 2px solid brown;
  min-height: 100px;
  display: flex;
  padding-top: 30px;
  background-color: rgb(246, 247, 251);
  margin-bottom: 20px;
  padding-bottom: 30px;
}

.pixelgrade-main-section {
  border: 2px solid blue;
  display: flex;
  align-items: center;
  min-height: 60px;
  justify-content: space-between;
}

.pixelgrade-left-section {
  border: 2px solid red;
  display: flex;
  flex-direction: column;
  width: 100%;
  gap: 10px;
  font-size: 28px;
  font-weight: 600;
}

.pixelgrade-left-section>span:first-child {
  line-height: 100%;
  color: #4D4D4D;
}

.pixelgrade-left-section>#span-sub-text {
  line-height: 100%;
  color: #4D4D4D;
}

.pixelgrade-left-section>small {
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  color: #717171;
}

.pixelgrade-left-section>span:first-child,
.pixelgrade-left-section>#span-sub-text,
.pixelgrade-left-section>small {
  text-align: center;
}

.pixelgrade-image {
  border: 2px solid purple;
  width: 38%;
  height: auto;
  display: none;
  justify-content: flex-end;
}

.pixelgrade-image > img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
  object-position: center;
}