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
            診断の拡張メソッドを<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。
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
            作成<see cref="T:System.Diagnostics.Activity" />に格納されているトレースのコンテキストに基づいて、 <see cref="T:Microsoft.Azure.EventHubs.EventData" /> <param name="eventData">EventHub から受信したイベント</param><param name="activityName">オプションのアクティビティ名</param><returns>新規<see cref="T:System.Diagnostics.Activity" />のトレースコンテキスト</returns></summary>
        <returns>To be added.</returns>
        <remarks>
            コンテキストのトレースはプロデューサーとコンシューマー間で製品利用統計情報を関連付けるために使用し、内の '診断 Id' および' コンテキスト相関関係 ' プロパティによって表される<see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" />です。
            
            .NET SDK は、(診断は、トレース システムで有効になっている) 場合は、ServiceBus にメッセージを送信するときにコンテキストを自動的に挿入します。
            
            <para>'Id の診断' を一意に識別操作イベントをエンキュー </para> <para> 'コンテキスト相関関係' は操作の省略可能なコンテキストを表すキー値のペアを文字列のコンマ区切り一覧。</para>
            
            このメソッドが戻るかどうかはコンテキストがないトレース イベントで、<see cref="T:System.Diagnostics.Activity" />親のないです。
            
            返される<see cref="T:System.Diagnostics.Activity" />を使用する前に起動する必要があります (次の例を参照してください)
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
            
            すべてのログがスタンプ注<see cref="P:System.Diagnostics.Activity.Current" />です。いずれかで使用可能な id には、メソッドの呼び出し (同期または非同期) が入れ子になった<see cref="P:System.Diagnostics.Activity.Current" />async メソッドの呼び出しと共に渡されるアンビエント コンテキストします。
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>