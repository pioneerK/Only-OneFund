<!doctype html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Only One Fund - 応援で繋がる挑戦のSNS</title>
  <script src="https://unpkg.com/@tanstack/react-query@5.28.0/build/umd/index.production.js"></script>
  <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
  <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Hiragino Sans', 'Hiragino Kaku Gothic ProN', 'Noto Sans JP', -apple-system, BlinkMacSystemFont, sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      width: 100%;
      height: 100%;
      overflow-x: hidden;
    }

    html, body, #root {
      height: 100%;
    }

    #root {
      width: 100%;
      height: 100%;
      overflow-y: auto;
      overflow-x: hidden;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      min-height: 100%;
      background: white;
      box-shadow: 0 0 40px rgba(0,0,0,0.1);
    }

    .welcome-screen {
      padding: 60px 24px;
      text-align: center;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .welcome-logo {
      width: 120px;
      height: 120px;
      margin-bottom: 24px;
      border-radius: 50%;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }

    .welcome-icon {
      font-size: 80px;
      margin-bottom: 24px;
    }

    .welcome-title {
      font-size: 32px;
      font-weight: bold;
      margin-bottom: 16px;
    }

    .welcome-subtitle {
      font-size: 18px;
      margin-bottom: 40px;
      opacity: 0.9;
    }

    .welcome-concept {
      background: rgba(255,255,255,0.15);
      backdrop-filter: blur(10px);
      border-radius: 16px;
      padding: 32px 24px;
      margin-bottom: 32px;
      text-align: left;
      max-width: 600px;
    }

    .welcome-concept h3 {
      font-size: 20px;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .welcome-concept p {
      font-size: 16px;
      line-height: 1.8;
      opacity: 0.95;
      margin-bottom: 12px;
    }

    .welcome-rules {
      background: rgba(255,255,255,0.15);
      backdrop-filter: blur(10px);
      border-radius: 16px;
      padding: 24px;
      margin-bottom: 32px;
      text-align: left;
      max-width: 600px;
    }

    .welcome-rules h4 {
      font-size: 16px;
      margin-bottom: 12px;
      opacity: 0.9;
    }

    .welcome-rules ul {
      list-style: none;
    }

    .welcome-rules li {
      font-size: 14px;
      padding: 8px 0;
      padding-left: 24px;
      position: relative;
      opacity: 0.9;
    }

    .welcome-rules li:before {
      content: "✓";
      position: absolute;
      left: 0;
      font-weight: bold;
    }

    .language-toggle {
      margin-bottom: 24px;
    }

    .language-button {
      background: rgba(255,255,255,0.2);
      border: 2px solid rgba(255,255,255,0.3);
      color: white;
      padding: 8px 20px;
      border-radius: 50px;
      fontSize: 14px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .language-button:hover {
      background: rgba(255,255,255,0.3);
      border-color: rgba(255,255,255,0.5);
    }

    .icon-selection {
      margin-bottom: 24px;
    }

    .icon-selection-label {
      display: block;
      font-size: 14px;
      margin-bottom: 12px;
      opacity: 0.95;
    }

    .icon-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 12px;
      max-width: 400px;
      margin: 0 auto;
    }

    .icon-option {
      width: 100%;
      aspect-ratio: 1;
      border: 3px solid rgba(255,255,255,0.3);
      border-radius: 16px;
      background: rgba(255,255,255,0.2);
      font-size: 32px;
      cursor: pointer;
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .icon-option:hover {
      background: rgba(255,255,255,0.3);
      border-color: rgba(255,255,255,0.6);
      transform: scale(1.1);
    }

    .icon-option.selected {
      background: white;
      border-color: white;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      transform: scale(1.15);
    }

    .welcome-input {
      width: 100%;
      padding: 12px 16px;
      border: 2px solid rgba(255,255,255,0.3);
      border-radius: 8px;
      font-size: 16px;
      background: rgba(255,255,255,0.2);
      color: white;
      font-family: inherit;
      transition: all 0.3s ease;
    }

    .welcome-input::placeholder {
      color: rgba(255,255,255,0.7);
    }

    .welcome-input:focus {
      outline: none;
      border-color: rgba(255,255,255,0.6);
      background: rgba(255,255,255,0.25);
      box-shadow: 0 0 0 3px rgba(255,255,255,0.1);
    }

    .btn-start {
      background: white;
      color: #667eea;
      border: none;
      padding: 16px 48px;
      border-radius: 50px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      transition: all 0.3s ease;
    }

    .btn-start:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.25);
    }

    .header {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      padding: 16px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-title {
      font-size: 20px;
      font-weight: bold;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .header-logo {
      width: 32px;
      height: 32px;
      border-radius: 50%;
    }

    .header-right {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .lang-button-small {
      background: rgba(255,255,255,0.2);
      border: none;
      color: white;
      padding: 6px 12px;
      border-radius: 50px;
      font-size: 12px;
      font-weight: bold;
      cursor: pointer;
    }

    .header-points {
      background: rgba(255,255,255,0.2);
      backdrop-filter: blur(10px);
      padding: 8px 16px;
      border-radius: 50px;
      font-size: 14px;
      font-weight: bold;
    }

    .points-number {
      font-size: 20px;
      margin-left: 4px;
    }

    .nav-tabs {
      display: flex;
      background: #f8f9fa;
      border-bottom: 2px solid #e9ecef;
      position: sticky;
      top: 60px;
      z-index: 99;
    }

    .nav-tab {
      flex: 1;
      padding: 16px;
      text-align: center;
      background: none;
      border: none;
      font-size: 14px;
      font-weight: 600;
      color: #6c757d;
      cursor: pointer;
      transition: all 0.3s ease;
      position: relative;
    }

    .nav-tab.active {
      color: #667eea;
      background: white;
    }

    .nav-tab.active:after {
      content: '';
      position: absolute;
      bottom: -2px;
      left: 0;
      right: 0;
      height: 2px;
      background: #667eea;
    }

    .feed {
      padding: 20px;
    }

    .earn-points-card {
      background: linear-gradient(135deg, #28a745 0%, #20c997 100%);
      border-radius: 16px;
      padding: 24px;
      margin-bottom: 24px;
      color: white;
      box-shadow: 0 4px 16px rgba(40, 167, 69, 0.3);
    }

    .earn-points-title {
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .earn-points-description {
      font-size: 14px;
      line-height: 1.6;
      opacity: 0.95;
      margin-bottom: 16px;
    }

    .btn-watch-ad {
      width: 100%;
      background: white;
      color: #28a745;
      border: none;
      padding: 14px;
      border-radius: 12px;
      font-size: 15px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .btn-watch-ad:hover:not(:disabled) {
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(255, 255, 255, 0.5);
    }

    .btn-watch-ad:disabled {
      background: rgba(255, 255, 255, 0.3);
      color: rgba(255, 255, 255, 0.7);
      cursor: not-allowed;
    }

    .category-filter {
      display: flex;
      gap: 8px;
      margin-bottom: 20px;
      overflow-x: auto;
      padding-bottom: 8px;
    }

    .filter-btn {
      padding: 8px 16px;
      border-radius: 50px;
      border: 2px solid #e9ecef;
      background: white;
      font-size: 13px;
      font-weight: 600;
      color: #495057;
      cursor: pointer;
      white-space: nowrap;
      transition: all 0.3s ease;
    }

    .filter-btn.active {
      background: #667eea;
      color: white;
      border-color: #667eea;
    }

    .fund-card {
      background: white;
      border-radius: 16px;
      padding: 20px;
      margin-bottom: 16px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      transition: all 0.3s ease;
      border: 2px solid #f8f9fa;
    }

    .fund-card:hover {
      box-shadow: 0 4px 16px rgba(0,0,0,0.12);
      border-color: #667eea;
    }

    .fund-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 12px;
    }

    .fund-title {
      font-size: 18px;
      font-weight: bold;
      color: #212529;
      margin-bottom: 8px;
    }

    .completed-badge {
      font-size: 14px;
      color: #28a745;
      font-weight: normal;
    }

    .category-badge {
      padding: 4px 12px;
      border-radius: 50px;
      font-size: 12px;
      font-weight: 600;
      white-space: nowrap;
    }

    .category-challenge { background: #fff3cd; color: #856404; }
    .category-creation { background: #d1ecf1; color: #0c5460; }
    .category-learning { background: #d4edda; color: #155724; }
    .category-social { background: #f8d7da; color: #721c24; }

    .fund-creator {
      font-size: 13px;
      color: #6c757d;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .fund-creator-icon {
      font-size: 16px;
    }

    .fund-description {
      font-size: 14px;
      line-height: 1.6;
      color: #495057;
      margin-bottom: 16px;
    }

    .progress-section {
      margin-bottom: 16px;
    }

    .progress-label {
      display: flex;
      justify-content: space-between;
      font-size: 13px;
      color: #6c757d;
      margin-bottom: 8px;
    }

    .progress-bar-bg {
      background: #e9ecef;
      height: 8px;
      border-radius: 50px;
      overflow: hidden;
    }

    .progress-bar-fill {
      background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
      height: 100%;
      border-radius: 50px;
      transition: width 0.5s ease;
    }

    .supporters-section {
      display: flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 16px;
    }

    .supporter-avatar {
      width: 32px;
      height: 32px;
      border-radius: 50%;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      font-weight: bold;
      border: 2px solid white;
      margin-left: -8px;
    }

    .supporter-avatar:first-child {
      margin-left: 0;
    }

    .supporter-count {
      font-size: 13px;
      color: #6c757d;
      margin-left: 4px;
    }

    .fund-actions {
      display: flex;
      gap: 8px;
    }

    .btn-support {
      flex: 1;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      border: none;
      padding: 12px 24px;
      border-radius: 50px;
      font-size: 14px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
    }

    .btn-support:hover:not(:disabled) {
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(102, 126, 234, 0.4);
    }

    .btn-support:disabled {
      background: #e9ecef;
      color: #adb5bd;
      cursor: not-allowed;
    }

    .profile {
      padding: 20px;
    }

    .profile-header {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      border-radius: 16px;
      padding: 32px 24px;
      color: white;
      text-align: center;
      margin-bottom: 24px;
    }

    .profile-avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
      margin: 0 auto 16px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 40px;
      border: 4px solid white;
    }

    .profile-name {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 8px;
    }

    .profile-badge {
      display: inline-block;
      padding: 6px 16px;
      border-radius: 50px;
      background: rgba(255,255,255,0.2);
      font-size: 14px;
      font-weight: 600;
      margin-bottom: 16px;
    }

    .profile-stats {
      display: flex;
      justify-content: space-around;
      margin-top: 20px;
    }

    .stat-item {
      text-align: center;
    }

    .stat-value {
      font-size: 28px;
      font-weight: bold;
      display: block;
    }

    .stat-label {
      font-size: 12px;
      opacity: 0.9;
      margin-top: 4px;
    }

    .premium-card {
      background: linear-gradient(135deg, #ffd700 0%, #ffed4e 100%);
      border-radius: 16px;
      padding: 24px;
      margin-bottom: 24px;
      color: #333;
      box-shadow: 0 4px 16px rgba(255, 215, 0, 0.4);
      border: 2px solid #ffc107;
    }

    .premium-title {
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .demo-badge {
      display: inline-block;
      background: rgba(255,255,255,0.8);
      color: #666;
      padding: 4px 12px;
      border-radius: 50px;
      font-size: 12px;
      font-weight: 600;
      margin-left: 8px;
    }

    .premium-benefits {
      background: rgba(255,255,255,0.5);
      border-radius: 12px;
      padding: 16px;
      margin-bottom: 16px;
    }

    .premium-benefit-item {
      font-size: 14px;
      padding: 8px 0;
      padding-left: 24px;
      position: relative;
      line-height: 1.6;
    }

    .premium-benefit-item:before {
      content: "✓";
      position: absolute;
      left: 0;
      font-weight: bold;
      color: #28a745;
    }

    .premium-price {
      text-align: center;
      margin-bottom: 16px;
    }

    .price-amount {
      font-size: 32px;
      font-weight: bold;
      color: #333;
    }

    .price-period {
      font-size: 14px;
      color: #666;
    }

    .btn-premium {
      width: 100%;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      border: none;
      padding: 16px;
      border-radius: 12px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .btn-premium:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(102, 126, 234, 0.5);
    }

    .requirement {
      background: #fff3cd;
      border-left: 4px solid #ffc107;
      padding: 12px;
      border-radius: 8px;
      font-size: 13px;
      color: #856404;
      margin-bottom: 24px;
    }

    .btn-create-fund {
      width: 100%;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      border: none;
      padding: 16px;
      border-radius: 12px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      margin-bottom: 24px;
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .btn-create-fund:hover:not(:disabled) {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
    }

    .btn-create-fund:disabled {
      background: #e9ecef;
      color: #adb5bd;
      cursor: not-allowed;
    }

    .section-title {
      font-size: 18px;
      font-weight: bold;
      color: #212529;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .empty-state {
      text-align: center;
      padding: 60px 20px;
      color: #6c757d;
    }

    .empty-icon {
      font-size: 64px;
      margin-bottom: 16px;
      opacity: 0.5;
    }

    .empty-text {
      font-size: 16px;
    }

    .create-fund-form {
      padding: 20px;
    }

    .premium-notice {
      background: #d4edda;
      border-left: 4px solid #28a745;
      padding: 12px;
      border-radius: 8px;
      font-size: 13px;
      color: #155724;
      margin-bottom: 24px;
    }

    .guideline-box {
      background: #d1ecf1;
      border-left: 4px solid #17a2b8;
      padding: 16px;
      border-radius: 8px;
      margin-bottom: 24px;
    }

    .guideline-title {
      font-size: 14px;
      font-weight: bold;
      color: #0c5460;
      margin-bottom: 8px;
    }

    .guideline-text {
      font-size: 13px;
      color: #0c5460;
      line-height: 1.6;
    }

    .form-group {
      margin-bottom: 24px;
    }

    .form-label {
      display: block;
      font-size: 14px;
      font-weight: 600;
      color: #495057;
      margin-bottom: 8px;
    }

    .form-input {
      width: 100%;
      padding: 12px 16px;
      border: 2px solid #e9ecef;
      border-radius: 8px;
      font-size: 14px;
      transition: all 0.3s ease;
      font-family: inherit;
    }

    .form-input:focus {
      outline: none;
      border-color: #667eea;
      box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
    }

    .form-textarea {
      min-height: 120px;
      resize: vertical;
    }

    .char-count {
      font-size: 12px;
      color: #6c757d;
      text-align: right;
      margin-top: 4px;
    }

    .category-select {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .category-option {
      padding: 16px;
      border: 2px solid #e9ecef;
      border-radius: 12px;
      text-align: center;
      cursor: pointer;
      transition: all 0.3s ease;
      background: white;
    }

    .category-option:hover {
      border-color: #667eea;
      background: #f8f9ff;
    }

    .category-option.selected {
      border-color: #667eea;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
    }

    .category-option-icon {
      font-size: 28px;
      margin-bottom: 8px;
    }

    .category-option-label {
      font-size: 14px;
      font-weight: 600;
    }

    .btn-submit {
      width: 100%;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      border: none;
      padding: 16px;
      border-radius: 12px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .btn-submit:hover:not(:disabled) {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
    }

    .btn-submit:disabled {
      background: #e9ecef;
      color: #adb5bd;
      cursor: not-allowed;
    }

    .modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.8);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 1000;
      animation: fadeIn 0.3s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .modal {
      background: white;
      border-radius: 16px;
      padding: 32px;
      max-width: 400px;
      width: 90%;
      text-align: center;
      animation: slideUp 0.3s ease;
    }

    @keyframes slideUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .ad-icon {
      font-size: 64px;
      margin-bottom: 16px;
    }

    .ad-title {
      font-size: 22px;
      font-weight: bold;
      color: #212529;
      margin-bottom: 12px;
    }

    .ad-message {
      font-size: 15px;
      color: #6c757d;
      line-height: 1.6;
      margin-bottom: 24px;
    }

    .ad-timer {
      font-size: 48px;
      font-weight: bold;
      color: #667eea;
      margin-bottom: 16px;
    }

    .ad-progress {
      background: #e9ecef;
      height: 8px;
      border-radius: 50px;
      overflow: hidden;
      margin-bottom: 24px;
    }

    .ad-progress-fill {
      background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
      height: 100%;
      border-radius: 50px;
      transition: width 0.3s ease;
    }

    .btn-close-ad {
      width: 100%;
      background: linear-gradient(135deg, #28a745 0%, #20c997 100%);
      color: white;
      border: none;
      padding: 14px;
      border-radius: 12px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .btn-close-ad:hover {
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(40, 167, 69, 0.4);
    }

    .scroll-top-button {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 50px;
      font-size: 12px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 4px 16px rgba(102, 126, 234, 0.4);
      z-index: 999;
      transition: all 0.3s ease;
    }

    .scroll-top-button:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(102, 126, 234, 0.6);
    }

    .toast {
      position: fixed;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
      background: #212529;
      color: white;
      padding: 16px 24px;
      borderRadius: 50px;
      font-size: 14px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.3);
      z-index: 1000;
      animation: slideUpToast 0.3s ease;
    }

    @keyframes slideUpToast {
      from {
        opacity: 0;
        transform: translate(-50%, 20px);
      }
      to {
        opacity: 1;
        transform: translate(-50%, 0);
      }
    }

    .toast.success {
      background: #28a745;
    }

    .toast.error {
      background: #dc3545;
    }

    @media (max-width: 600px) {
      .welcome-title {
        font-size: 24px;
      }
      
      .welcome-subtitle {
        font-size: 16px;
      }

      .category-select {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <div id="root"></div>

  <script type="text/babel">
    const { useState, useEffect, useRef, createElement: h } = React;

    // Note: このHTMLファイルはBase44プラットフォーム上でのみ動作します
    // base44 SDKが必要です

    // 翻訳データ
    const translations = {
      ja: {
        appTitle: 'Only One Fund',
        welcomeTitle: 'Only One Fundへようこそ',
        welcomeSubtitle: '挑戦と応援でつなぐ新しいSNS',
        conceptTitle: 'このアプリの思想',
        conceptText1: 'あなたには10ポイントが与えられます。',
        conceptText2: '1ポイントは「お金」ではなく、',
        conceptText2Bold: '「承認」「応援」',
        conceptText2After: 'の形です。',
        conceptText3: '誰かの挑戦・学習・創作を応援することで、あなたの影響力が記録され、関係性が可視化されます。',
        conceptText4: '広告を見ることでポイントを追加獲得できます。',
        rulesTitle: '基本ルール',
        rule1: '初期ポイント10pt（広告視聴で増やせる）',
        rule2: '1ファンドに1回のみ応援可能',
        rule3: 'ファンド作成には5回以上応援が必要',
        rule4: '月1回までファンド作成可能（プレミアムで3回）',
        rule5: '目標は成長や学び・社会貢献につながるもの',
        selectIcon: 'あなたのアイコンを選んでください',
        enterName: '表示名を入力してください',
        namePlaceholder: '例：田中太郎',
        startButton: '始める',
        home: 'ホーム',
        profile: 'プロフィール',
        create: '作成',
        remainingPoints: '残り',
        earnPointsTitle: 'ポイントを獲得しよう',
        earnPointsDesc: '広告を視聴して1ポイント獲得できます。獲得したポイントでさらに多くの挑戦を応援しましょう！',
        watchAdButton: '広告を見て+1pt獲得',
        allCategory: 'すべて',
        challenge: '挑戦',
        creation: '創作',
        learning: '学習',
        social: '社会',
        progress: '進捗',
        supporters: '人が応援',
        support: '応援する',
        pointsShort: 'pt',
        pointsShortage: 'ポイント不足',
        alreadySupported: '応援済み',
        myFund: '自分のファンド',
        by: 'by',
        completed: '達成済み',
        receivedSupports: '受けた応援',
        supportedFunds: '応援した数',
        premiumTitle: 'プレミアム会員',
        demoLabel: 'デモ表示',
        premiumBenefit1: '月3回までファンド作成可能（通常は月1回）',
        premiumBenefit2: '目標ポイント上限200pt（通常は100pt）',
        premiumBenefit3: 'プレミアムバッジ表示',
        premiumBenefit4: '優先的なサポート対応',
        monthlyPrice: '¥980',
        perMonth: '/月額',
        becomePremium: 'プレミアム会員になる',
        createNewFund: '新しいファンドを作る',
        requirementTitle: 'ファンド作成の条件',
        requirementText: '5回以上他の人のファンドを応援する必要があります（現在{count}回応援）',
        supportedTitle: '応援した挑戦',
        myFundsTitle: '自分のファンド',
        noSupported: 'まだ応援していません',
        noMyFunds: 'まだファンドを作成していません',
        createFundTitle: '新しいファンドを作る',
        monthlyLimitReached: '今月はすでにファンドを作成済みです。次回作成は来月まで待つ必要があります。',
        premiumBenefitNotice: 'プレミアム会員特典: 月{limit}回まで作成可能、目標ポイント最大{max}pt',
        guidelineTitle: 'ファンド作成のガイドライン',
        guidelineText: 'あなたの成長や学び、社会への貢献につながる最終目標を記載してください。そこに至るまでのプロセス（必要な物品購入、旅行など）は、目標達成のために必要であれば問題ありません。',
        categoryLabel: 'カテゴリ',
        titleLabel: 'タイトル',
        titlePlaceholder: '例：プログラミングスキルを習得する',
        descriptionLabel: '目標の説明',
        descriptionPlaceholder: 'この挑戦の最終目標や意義を説明してください（200文字以内）',
        targetPointsLabel: '目標ポイント',
        targetPointsPlaceholder: '例：20',
        targetPointsRange: '5〜{max}ptの範囲で設定してください',
        createFundButton: 'ファンドを作成する',
        backToProfile: 'プロフィールに戻る',
        cannotCreate: 'ファンドを作成できません',
        selectCategory: 'カテゴリを選択してください',
        invalidTargetPoints: '目標ポイントは5〜{max}の範囲で設定してください',
        fundCreated: 'ファンドを作成しました！',
        supportSent: '応援を送りました！',
        pointEarned: '1ポイント獲得しました！',
        accountCreated: 'アカウントを作成しました！',
        watchingAd: '広告を視聴中...',
        pleaseWait: '5秒間お待ちください',
        pointGained: '+1ポイント獲得！',
        closeButton: '閉じる',
        premiumPurchase: 'プレミアム会員登録',
        demoMessage: 'この機能はデモ表示です。実際の課金機能は実装されていません。',
        scrollToTop: 'トップに戻る'
      },
      en: {
        appTitle: 'Only One Fund',
        welcomeTitle: 'Welcome to Only One Fund',
        welcomeSubtitle: 'A new SNS connecting challenges and support',
        conceptTitle: 'Our Philosophy',
        conceptText1: 'You start with 10 points.',
        conceptText2: '1 point is not "money", but a form of ',
        conceptText2Bold: '"recognition" and "support"',
        conceptText2After: '.',
        conceptText3: 'By supporting others\' challenges, learning, and creations, your influence is recorded and relationships are visualized.',
        conceptText4: 'You can earn additional points by watching ads.',
        rulesTitle: 'Basic Rules',
        rule1: 'Start with 10 points (earn more by watching ads)',
        rule2: 'Support each fund only once',
        rule3: 'Need to support 5+ funds to create your own',
        rule4: 'Create 1 fund per month (3 with Premium)',
        rule5: 'Goals should contribute to growth, learning, or society',
        selectIcon: 'Choose your icon',
        enterName: 'Enter your display name',
        namePlaceholder: 'e.g., John Doe',
        startButton: 'Start',
        home: 'Home',
        profile: 'Profile',
        create: 'Create',
        remainingPoints: 'Remaining',
        earnPointsTitle: 'Earn More Points',
        earnPointsDesc: 'Watch an ad to earn 1 point. Use earned points to support more challenges!',
        watchAdButton: 'Watch ad for +1pt',
        allCategory: 'All',
        challenge: 'Challenge',
        creation: 'Creation',
        learning: 'Learning',
        social: 'Social',
        progress: 'Progress',
        supporters: 'supporters',
        support: 'Support',
        pointsShort: 'pt',
        pointsShortage: 'Not enough points',
        alreadySupported: 'Supported',
        myFund: 'My fund',
        by: 'by',
        completed: 'Completed',
        receivedSupports: 'Supports Received',
        supportedFunds: 'Funds Supported',
        premiumTitle: 'Premium Membership',
        demoLabel: 'Demo',
        premiumBenefit1: 'Create up to 3 funds per month (normally 1)',
        premiumBenefit2: 'Target points up to 200pt (normally 100pt)',
        premiumBenefit3: 'Premium badge display',
        premiumBenefit4: 'Priority support',
        monthlyPrice: '$9.80',
        perMonth: '/month',
        becomePremium: 'Become Premium',
        createNewFund: 'Create New Fund',
        requirementTitle: 'Fund Creation Requirement',
        requirementText: 'You need to support 5+ funds (currently {count} supported)',
        supportedTitle: 'Supported Challenges',
        myFundsTitle: 'My Funds',
        noSupported: 'No supported funds yet',
        noMyFunds: 'No funds created yet',
        createFundTitle: 'Create New Fund',
        monthlyLimitReached: 'You have already created a fund this month. Please wait until next month.',
        premiumBenefitNotice: 'Premium benefit: Create up to {limit} times per month, max target {max}pt',
        guidelineTitle: 'Fund Creation Guidelines',
        guidelineText: 'Describe your final goal that contributes to your growth, learning, or society. The process to achieve it (purchasing necessary items, travel, etc.) is acceptable if needed for the goal.',
        categoryLabel: 'Category',
        titleLabel: 'Title',
        titlePlaceholder: 'e.g., Learn programming skills',
        descriptionLabel: 'Goal Description',
        descriptionPlaceholder: 'Describe the final goal and significance of this challenge (max 200 chars)',
        targetPointsLabel: 'Target Points',
        targetPointsPlaceholder: 'e.g., 20',
        targetPointsRange: 'Set between 5-{max}pt',
        createFundButton: 'Create Fund',
        backToProfile: 'Back to Profile',
        cannotCreate: 'Cannot create fund',
        selectCategory: 'Please select a category',
        invalidTargetPoints: 'Target points must be between 5-{max}',
        fundCreated: 'Fund created!',
        supportSent: 'Support sent!',
        pointEarned: 'Earned 1 point!',
        accountCreated: 'Account created!',
        watchingAd: 'Watching ad...',
        pleaseWait: 'Please wait 5 seconds',
        pointGained: '+1 point gained!',
        closeButton: 'Close',
        premiumPurchase: 'Premium Membership Registration',
        demoMessage: 'This is a demo feature. Actual payment functionality is not implemented.',
        scrollToTop: 'Back to Top'
      }
    };

    console.log('このHTMLファイルはBase44プラットフォーム上で動作するために作られています。');
    console.log('ローカルでは動作しません。Base44にデプロイしてご使用ください。');

    // アプリケーションコンポーネント
    function App() {
      return h('div', { className: 'welcome-screen' },
        h('div', { className: 'welcome-icon' }, '🎯'),
        h('h1', { className: 'welcome-title' }, 'Only One Fund'),
        h('p', { className: 'welcome-subtitle' }, 'このアプリはBase44プラットフォーム上で動作します'),
        h('div', { style: { marginTop: '20px', fontSize: '14px', opacity: 0.9 } },
          'pages/Home.js をBase44にアップロードしてご使用ください'
        )
      );
    }

    // レンダリング
    const root = ReactDOM.createRoot(document.getElementById('root'));
    root.render(h(App));
  </script>
</body>
</html>
