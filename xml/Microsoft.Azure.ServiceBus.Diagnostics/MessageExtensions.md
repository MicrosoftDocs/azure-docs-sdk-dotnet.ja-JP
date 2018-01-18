<Type Name="MessageExtensions" FullName="Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions">
  <TypeSignature Language="C#" Value="public static class MessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MessageExtensions" />
  <TypeSignature Language="F#" Value="type MessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtractActivity">
      <MemberSignature Language="C#" Value="public static System.Diagnostics.Activity ExtractActivity (this Microsoft.Azure.ServiceBus.Message message, string activityName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Diagnostics.Activity ExtractActivity(class Microsoft.Azure.ServiceBus.Message message, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions.ExtractActivity(Microsoft.Azure.ServiceBus.Message,System.String)" />
      <MemberSignature Language="F#" Value="static member ExtractActivity : Microsoft.Azure.ServiceBus.Message * string -&gt; System.Diagnostics.Activity" Usage="Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions.ExtractActivity (message, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Diagnostics.Activity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" RefType="this" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <param name="activityName">To be added.</param>
        <summary>
            <span data-ttu-id="72ad2-101">作成<see cref="T:System.Diagnostics.Activity" />に格納されているトレースのコンテキストに基づいて、 <see cref="T:Microsoft.Azure.ServiceBus.Message" /><param name="activityName">オプションのアクティビティ名</param><returns>新規<see cref="T:System.Diagnostics.Activity" />トレース コンテキストを持つ</returns></span><span class="sxs-lookup"><span data-stu-id="72ad2-101">Creates <see cref="T:System.Diagnostics.Activity" /> based on the tracing context stored in the <see cref="T:Microsoft.Azure.ServiceBus.Message" /><param name="activityName">Optional Activity name</param><returns>New <see cref="T:System.Diagnostics.Activity" /> with tracing context</returns></span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="72ad2-102">コンテキストのトレースはプロデューサーとコンシューマー間で製品利用統計情報を関連付けるために使用し、内の '診断 Id' および' コンテキスト相関関係 ' プロパティによって表される<see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />です。</span><span class="sxs-lookup"><span data-stu-id="72ad2-102">Tracing context is used to correlate telemetry between producer and consumer and represented by 'Diagnostic-Id' and 'Correlation-Context' properties in <see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />.</span></span>
            
            <span data-ttu-id="72ad2-103">.NET SDK は、(診断は、トレース システムで有効になっている) 場合は、ServiceBus にメッセージを送信するときにコンテキストを自動的に挿入します。</span><span class="sxs-lookup"><span data-stu-id="72ad2-103">.NET SDK automatically injects context when sending message to the ServiceBus (if diagnostics is enabled by tracing system).</span></span>
            
            <span data-ttu-id="72ad2-104"><para>'Id の診断' を一意に識別操作にキュー入れられたメッセージ</para> <para> 'コンテキスト相関関係' は文字列のキー値のペア represeting 省略可能な操作のコンテキストのコンマ区切り一覧。</para></span><span class="sxs-lookup"><span data-stu-id="72ad2-104"><para> 'Diagnostic-Id' uniquely identifies operation that enqueued message </para><para> 'Correlation-Context' is comma separated list of sting key value pairs represeting optional context for the operation. </para></span></span>
            
            <span data-ttu-id="72ad2-105">このメソッドが戻るかどうかはコンテキストがないトレース メッセージで、<see cref="T:System.Diagnostics.Activity" />親のないです。</span><span class="sxs-lookup"><span data-stu-id="72ad2-105">If there is no tracing context in the message, this method returns <see cref="T:System.Diagnostics.Activity" /> without parent.</span></span>
            
            <span data-ttu-id="72ad2-106">返される<see cref="T:System.Diagnostics.Activity" />を使用する前に起動する必要があります (次の例を参照してください)</span><span class="sxs-lookup"><span data-stu-id="72ad2-106">Returned <see cref="T:System.Diagnostics.Activity" /> needs to be started before it can be used (see example below)</span></span>
            </remarks>
        <example>
          <code>
            async Task ProcessAsync()
            {
               var message = await messageReceiver.ReceiveAsync();
               var activity = message.ExtractActivity();
               activity.Start();
               Logger.LogInformation($"Message received, Id = {Activity.Current.Id}")
               try 
               {
                  // process message
               }
               catch (Exception ex)
               {
                    Logger.LogError($"Exception {ex}, Id = {Activity.Current.Id}")
               }
               finally 
               {
                    activity.Stop();
                    // Activity is stopped, we no longer have it in Activity.Current, let's user activity now
                    Logger.LogInformation($"Message processed, Id = {activity.Id}, Duration = {activity.Duration}")
               }
            }
            </code>
            
            <span data-ttu-id="72ad2-107">すべてのログがスタンプ注<see cref="P:System.Diagnostics.Activity.Current" />です。いずれかで使用可能な id には、メソッドの呼び出し (同期または非同期) が入れ子になった<see cref="P:System.Diagnostics.Activity.Current" />async メソッドの呼び出しと共に渡されるアンビエント コンテキストします。</span><span class="sxs-lookup"><span data-stu-id="72ad2-107">Note that every log is stamped with <see cref="P:System.Diagnostics.Activity.Current" />.Id, that could be used within any nested method call (sync or async) - <see cref="P:System.Diagnostics.Activity.Current" /> is an ambient context that flows with async method calls.</span></span>
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>