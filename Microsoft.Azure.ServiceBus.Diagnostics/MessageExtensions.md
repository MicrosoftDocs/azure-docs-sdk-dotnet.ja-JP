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
            作成<see cref="T:System.Diagnostics.Activity" />に格納されているトレースのコンテキストに基づいて、 <see cref="T:Microsoft.Azure.ServiceBus.Message" /><param name="activityName">オプションのアクティビティ名</param><returns>新規<see cref="T:System.Diagnostics.Activity" />トレース コンテキストを持つ</returns></summary>
        <returns>To be added.</returns>
        <remarks>
            コンテキストのトレースはプロデューサーとコンシューマー間で製品利用統計情報を関連付けるために使用し、内の '診断 Id' および' コンテキスト相関関係 ' プロパティによって表される<see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />です。
            
            .NET SDK は、(診断は、トレース システムで有効になっている) 場合は、ServiceBus にメッセージを送信するときにコンテキストを自動的に挿入します。
            
            <para>'Id の診断' を一意に識別操作にキュー入れられたメッセージ</para> <para> 'コンテキスト相関関係' は文字列のキー値のペア represeting 省略可能な操作のコンテキストのコンマ区切り一覧。</para>
            
            このメソッドが戻るかどうかはコンテキストがないトレース メッセージで、<see cref="T:System.Diagnostics.Activity" />親のないです。
            
            返される<see cref="T:System.Diagnostics.Activity" />を使用する前に起動する必要があります (次の例を参照してください)
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
            
            すべてのログがスタンプ注<see cref="P:System.Diagnostics.Activity.Current" />です。いずれかで使用可能な id には、メソッドの呼び出し (同期または非同期) が入れ子になった<see cref="P:System.Diagnostics.Activity.Current" />async メソッドの呼び出しと共に渡されるアンビエント コンテキストします。
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>