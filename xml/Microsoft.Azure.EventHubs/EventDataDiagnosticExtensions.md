<Type Name="EventDataDiagnosticExtensions" FullName="Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions">
  <TypeSignature Language="C#" Value="public static class EventDataDiagnosticExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventDataDiagnosticExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventDataDiagnosticExtensions" />
  <TypeSignature Language="F#" Value="type EventDataDiagnosticExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68570-101">診断の拡張メソッドを<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</span><span class="sxs-lookup"><span data-stu-id="68570-101">Diagnostic extension methods for <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtractActivity">
      <MemberSignature Language="C#" Value="public static System.Diagnostics.Activity ExtractActivity (this Microsoft.Azure.EventHubs.EventData eventData, string activityName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Diagnostics.Activity ExtractActivity(class Microsoft.Azure.EventHubs.EventData eventData, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions.ExtractActivity(Microsoft.Azure.EventHubs.EventData,System.String)" />
      <MemberSignature Language="F#" Value="static member ExtractActivity : Microsoft.Azure.EventHubs.EventData * string -&gt; System.Diagnostics.Activity" Usage="Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions.ExtractActivity (eventData, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Diagnostics.Activity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" RefType="this" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventData">To be added.</param>
        <param name="activityName">To be added.</param>
        <summary>
            <span data-ttu-id="68570-102">作成<see cref="T:System.Diagnostics.Activity" />に格納されているトレースのコンテキストに基づいて、 <see cref="T:Microsoft.Azure.EventHubs.EventData" /> <param name="eventData">EventHub から受信したイベント</param><param name="activityName">オプションのアクティビティ名</param><returns>新規<see cref="T:System.Diagnostics.Activity" />のトレースコンテキスト</returns></span><span class="sxs-lookup"><span data-stu-id="68570-102">Creates <see cref="T:System.Diagnostics.Activity" /> based on the tracing context stored in the <see cref="T:Microsoft.Azure.EventHubs.EventData" /><param name="eventData">The event received from EventHub</param><param name="activityName">Optional Activity name</param><returns>New <see cref="T:System.Diagnostics.Activity" /> with tracing context</returns></span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="68570-103">コンテキストのトレースはプロデューサーとコンシューマー間で製品利用統計情報を関連付けるために使用し、内の '診断 Id' および' コンテキスト相関関係 ' プロパティによって表される<see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" />です。</span><span class="sxs-lookup"><span data-stu-id="68570-103">Tracing context is used to correlate telemetry between producer and consumer and represented by 'Diagnostic-Id' and 'Correlation-Context' properties in <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" />.</span></span>
            
            <span data-ttu-id="68570-104">.NET SDK は、(診断は、トレース システムで有効になっている) 場合は、ServiceBus にメッセージを送信するときにコンテキストを自動的に挿入します。</span><span class="sxs-lookup"><span data-stu-id="68570-104">.NET SDK automatically injects context when sending message to the ServiceBus (if diagnostics is enabled by tracing system).</span></span>
            
            <span data-ttu-id="68570-105"><para>'Id の診断' を一意に識別操作イベントをエンキュー </para> <para> 'コンテキスト相関関係' は操作の省略可能なコンテキストを表すキー値のペアを文字列のコンマ区切り一覧。</para></span><span class="sxs-lookup"><span data-stu-id="68570-105"><para> 'Diagnostic-Id' uniquely identifies operation that enqueued the event </para><para> 'Correlation-Context' is comma separated list of string key value pairs representing optional context for the operation. </para></span></span>
            
            <span data-ttu-id="68570-106">このメソッドが戻るかどうかはコンテキストがないトレース イベントで、<see cref="T:System.Diagnostics.Activity" />親のないです。</span><span class="sxs-lookup"><span data-stu-id="68570-106">If there is no tracing context in the event, this method returns <see cref="T:System.Diagnostics.Activity" /> without parent.</span></span>
            
            <span data-ttu-id="68570-107">返される<see cref="T:System.Diagnostics.Activity" />を使用する前に起動する必要があります (次の例を参照してください)</span><span class="sxs-lookup"><span data-stu-id="68570-107">Returned <see cref="T:System.Diagnostics.Activity" /> needs to be started before it can be used (see example below)</span></span>
            </remarks>
        <example>
          <code>
            async Task ProcessAsync(EventData eventData)
            {
               var activity = eventData.ExtractActivity();
               activity.Start();
               Logger.LogInformation($"Event received, Id = {Activity.Current.Id}")
               try 
               {
                  // process event
               }
               catch (Exception ex)
               {
                    Logger.LogError($"Exception {ex}, Id = {Activity.Current.Id}")
               }
               finally 
               {
                    activity.Stop();
                    // Activity is stopped, we no longer have it in Activity.Current
                    Logger.LogInformation($"Event processed, Id = {activity.Id}, Duration = {activity.Duration}")
               }
            }
            </code>
            
            <span data-ttu-id="68570-108">すべてのログがスタンプ注<see cref="P:System.Diagnostics.Activity.Current" />です。いずれかで使用可能な id には、メソッドの呼び出し (同期または非同期) が入れ子になった<see cref="P:System.Diagnostics.Activity.Current" />async メソッドの呼び出しと共に渡されるアンビエント コンテキストします。</span><span class="sxs-lookup"><span data-stu-id="68570-108">Note that every log is stamped with <see cref="P:System.Diagnostics.Activity.Current" />.Id, that could be used within any nested method call (sync or async) - <see cref="P:System.Diagnostics.Activity.Current" /> is an ambient context that flows with async method calls.</span></span>
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>