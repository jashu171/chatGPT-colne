# 🚀 N8N Webhook Integration - Quick Start

## What You Have Now

Your AI chatbot is **already equipped** with N8N webhook integration! Here's what's working:

✅ **Webhook UI**: Lightning bolt (⚡) button in chat interface  
✅ **Backend API**: `/api/webhook` endpoint ready to use  
✅ **Error Handling**: Comprehensive error management  
✅ **Response Formatting**: Beautiful JSON display  
✅ **Default URL**: Pre-configured for `http://localhost:5678/webhook-test/chicago`

## 🏃‍♂️ Quick Start (2 Minutes)

### Step 1: Start Your Apps
```bash
# Terminal 1: Start your Flask app
python app.py

# Terminal 2: Start N8N
npx n8n
```

### Step 2: Create N8N Webhook
1. Go to http://localhost:5678
2. Create new workflow
3. Add "Webhook" node:
   - Path: `webhook-test/chicago`
   - Method: `GET`
4. Add "Respond to Webhook" node
5. Connect them and activate workflow

### Step 3: Test It!
1. Go to http://localhost:4000/chat
2. Click the ⚡ webhook button
3. Click "Call Webhook"
4. See the magic happen! ✨

## 🎯 What Happens

```
Your Chat → Flask App → N8N Webhook → Your Workflow → Response → Chat Display
```

## 📁 Files Created

- `N8N_WEBHOOK_INTEGRATION_GUIDE.md` - Complete documentation
- `test_n8n_webhook.py` - Test script
- `setup_n8n_integration.py` - Setup helper
- `n8n_example_workflow.json` - Import this into N8N!

## 🔧 Quick Test

Run the test script to verify everything:
```bash
python test_n8n_webhook.py
```

## 🆘 Need Help?

1. **Flask not starting?** Check if port 4000 is free
2. **N8N not working?** Install with `npm install -g n8n`
3. **Webhook not responding?** Make sure N8N workflow is active
4. **Still stuck?** Check the full guide: `N8N_WEBHOOK_INTEGRATION_GUIDE.md`

## 🎉 You're Ready!

Your webhook integration is **complete and ready to use**. Start building amazing N8N workflows and watch your chatbot come alive with automation powers!

---
*Happy automating! 🤖⚡*
