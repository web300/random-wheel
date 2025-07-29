 <div class="container">
            <section>
            <h2><i class="bi bi-gas-pump-fill me-2"></i>最新油價</h2>
            <div class="row g-4">
                <div class="col-lg-6">
                    <div class="card shadow-sm price-card">
                        <h5><i class="bi bi-building"></i> 台灣中油 (CPC)</h5>
                        <div class="card-body">
                            <ul class="list-unstyled">
                                <li class="price-list-item">
                                    <span>92無鉛汽油</span>
                                    <span class="price-value up" id="latest-a92-container"><span id="latest-a92">26.9</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>95無鉛汽油</span>
                                    <span class="price-value up" id="latest-a95-container"><span id="latest-a95">28.4</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>98無鉛汽油</span>
                                    <span class="price-value up" id="latest-a98-container"><span id="latest-a98">30.4</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>超級柴油</span>
                                    <span class="price-value up" id="latest-achai-container"><span id="latest-achai">25.7</span> 元/公升</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="card shadow-sm price-card">
                        <h5><i class="bi bi-building"></i> 台塑石化 (Formosa)</h5>
                        <div class="card-body">
                             <ul class="list-unstyled">
                                <li class="price-list-item">
                                    <span>92+無鉛汽油</span>
                                    <span class="price-value up" id="latest-b92-container"><span id="latest-b92">26.9</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>95+無鉛汽油</span>
                                    <span class="price-value up" id="latest-b95-container"><span id="latest-b95">28.4</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>98無鉛汽油</span>
                                    <span class="price-value up" id="latest-b98-container"><span id="latest-b98">30.4</span> 元/公升</span>
                                </li>
                                <li class="price-list-item">
                                    <span>超級柴油</span>
                                    <span class="price-value up" id="latest-bchai-container"><span id="latest-bchai">25.5</span> 元/公升</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
   <section>
            <h2><i class="bi bi-gas-pump-fill me-2"></i>台灣郵編查詢</h2>
            <div class="row g-4">




<div class="col-md-4">
          <label for="city" class="form-label">第一步：選擇省份</label>
          <select id="city" class="form-select">
            <option value="">請選擇省份</option>
            <option value="1">臺北市</option>
            <option value="2">基隆市</option>
            <option value="3">新北市</option>
            <option value="4">連江縣</option>
            <option value="5">宜蘭縣</option>
            <option value="6">新竹市</option>
            <option value="7">新竹縣</option>
            <option value="8">桃園市</option>
            <option value="9">苗栗縣</option>
            <option value="10">臺中市</option>
            <option value="11">彰化縣</option>
            <option value="12">南投縣</option>
            <option value="13">嘉義市</option>
            <option value="14">嘉義縣</option>
            <option value="15">雲林縣</option>
            <option value="16">臺南市</option>
            <option value="17">高雄市</option>
            <option value="18">南海諸</option>
            <option value="19">澎湖縣</option>
            <option value="20">金門縣</option>
            <option value="21">屏東縣</option>
            <option value="22">臺東縣</option>
            <option value="23">花蓮縣</option>
          </select>

</div>
      <div class="col-md-4">
        <div class="mb-3">
          <label for="area" class="form-label">第二步：選擇城市</label>
          <select id="area" class="form-select" disabled>
            <option value="">請選擇省份</option>
          </select>
        </div>
      </div>
      <div class="col-md-4">
        <div class="mb-3">
          <label for="road" class="form-label">第三步：選擇區縣</label>
          <select id="road" class="form-select" disabled>
            <option value="">請先選擇省份</option>
          </select>
        </div>
      </div>

      <div id="result-container" class="d-none">
    <div class="card border-success">
        <div class="card-header bg-success text-white">
            <h3 class="card-title mb-0">
 查詢結果
            </h3>
        </div>
        <div id="zipcode-list" class="list-group list-group-flush">
        </div>
    </div>
</div>
    
<div id="loading" style="display: none;">
 正在加載數據...
</div>
<div id="empty-state" class="alert alert-warning alert-dismissible fade show" role="alert" style="display: none;">
  沒有找到匹配的數據
  <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
</div>
<div id="error-state" class="alert alert-danger alert-dismissible fade show" role="alert" style="display: none;">
  加載數據時出錯，請稍後重試
  <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
</div>
  
  </div>
        </section>   
        <section>
            <h2><i class="bi bi-newspaper me-2"></i>TOOLS</h2>
 <div class="row g-4">
    <div class="col-md-6 col-lg-4">
        <a href="https://zip.886life.com" class="text-decoration-none">
            <div class="card shadow-sm article-card">
                <div class="article-content">
                    <h5 class="article-title"><span class="hot-tag">郵編</span>台灣郵編查詢</h5>
                    <p class="article-excerpt">提供全面、準確的台灣郵政編碼查詢服務，覆蓋所有行政區域，幫助您快速找到所需地區的郵政編碼。</p>
   
                </div>
            </div>
        </a>
    </div>

                <div class="col-md-6 col-lg-4">
                    <a href="/tools/fangdai.html" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title"><span class="hot-tag">房貸</span>房貸計算器</h5>
                            <p class="article-excerpt">使用房貸計算器輕鬆計算台灣房貸的每月還款金額，支援貸款總金額、貸款年限、利率等多種設置，幫助您了解房貸支付情況。</p>
                
                        </div>
                    </div> </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="/tools/youjia.html" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title"><span class="hot-tag">油價</span>最新油價資訊與走勢圖</h5>
                            <p class="article-excerpt">提供最新的油價資訊及走勢圖，讓您了解全球及台灣油價波動，輕鬆掌握油價變化趨勢，協助您做出最佳的加油決策。</p>
                     
                        </div>
                    </div></a>
                </div>
                   <div class="col-md-6 col-lg-4">
                    <a href="https://time.886life.com/tw/taipei/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title"><span class="hot-tag">時間</span>臺灣省台北時間</h5>
                            <p class="article-excerpt">台灣採用單一時區，稱為國家標準時間或台灣時間。</p>
                     
                        </div>
                    </div></a>
                </div>
                  <div class="col-md-6 col-lg-4">
                    <a href="/tools/wordcount.html" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title"><span class="hot-tag">計數</span>文字計數工具</h5>
                            <p class="article-excerpt">多功能文字統計與處理工具，支持多種統計維度和段落整理。</p>
                     
                        </div>
                    </div></a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="/tools/gbk-big5-gb2312-utf8.html" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title"><span class="hot-tag">繁簡</span>繁簡轉換工具</h5>
                            <p class="article-excerpt">簡體轉繁體、繁體轉簡體，支持GBK與BIG5編碼互轉。</p>
                     
                        </div>
                    </div></a>
                </div>
                
                           <div class="col-md-6 col-lg-4">
                     <a href="https://instagram.886life.com/tw/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">字體</span>
                                Instagram 字體工具
                            </h5>
                            <p class="article-excerpt">在第一個框中輸入文本後，文本生成器將實時將其轉換為多種字體樣式。您可以複製轉換後的文本並粘貼到 Instagram、Twitter 或 Facebook 上，適用於簽名、照片說明和評論。</p>
                       
                        </div>
                    </div></a>
                </div>
                   <div class="col-md-6 col-lg-4">
                    <a href="https://random-wheel.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">輪盤</span>
                                Random Wheel
                            </h5>
                            <p class="article-excerpt">Experience realistic 3D rolling effects and the fun of randomness</p>
                    
                        </div>
                    </div></a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="https://rili.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">日曆</span>
                                農曆日曆
                            </h5>
                            <p class="article-excerpt">農曆日曆查詢工具 | 提供詳細的農曆、節氣、宜忌等信息。</p>
                      
                        </div>
                    </div></a>
                </div>
                 <div class="col-md-6 col-lg-4">
                    <a href="https://emoji.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">符號</span>
                               emoji 符號
                            </h5>
                            <p class="article-excerpt">All iOS devices, Android 4.4+, and Windows 8.1+ can display colorful emojis natively.</p>
                        
                        </div>
                    </div></a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="https://x-symbols.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">符號</span>
                               facebook 符號
                            </h5>
                            <p class="article-excerpt">只需單擊一個圖示即可將表情符號複製到剪貼簿。</p>
                     
                        </div>
                    </div></a>
                </div>
                
                      <div class="col-md-6 col-lg-4">
                    <a href="https://cool-text.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">酷文</span>
                               酷文字產生器
                            </h5>
                            <p class="article-excerpt">探索我們的字體生成器，這是一個創建時尚獨特文字的終極線上工具！</p>
                   
                        </div>
                    </div></a>
                </div>
                 <div class="col-md-6 col-lg-4">
                    <a href="https://random-dice.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">骰子</span>
                               骰子模擬器
                            </h5>
                            <p class="article-excerpt">體驗逼真的3D滾動效果，感受隨機的樂趣</p>
                   
                        </div>
                    </div></a>
                </div>
                        <div class="col-md-6 col-lg-4">
                    <a href="https://symbol.886life.com/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">符號</span>
                               ✪符號大全
                            </h5>
                            <p class="article-excerpt">這裡收集了各種分類的特殊符號，點擊符號即可複製。</p>
                   
                        </div>
                    </div></a>
                </div>
                  <div class="col-md-6 col-lg-4">
                    <a href="https://100.886life.com/tw/" class="text-decoration-none">
                    <div class="card shadow-sm article-card">
                        <div class="article-content">
                            <h5 class="article-title">
                                <span class="hot-tag">100</span>
                               百分比計算器
                            </h5>
                            <p class="article-excerpt">百分比計算器是一款實用的線上工具，可幫助您快速解決各種百分比計算問題。</p>
                   
                        </div>
                    </div></a>
                </div>
            </div>
        </section>

    </div>
