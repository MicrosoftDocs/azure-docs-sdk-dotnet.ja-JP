<Type Name="IWithMessageLockDuration" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration">
  <TypeSignature Language="C#" Value="public interface IWithMessageLockDuration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageLockDuration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageLockDuration" />
  <TypeSignature Language="F#" Value="type IWithMessageLockDuration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            メッセージのロックの期間を定義するようにサブスクリプション定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageLockDurationInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds (int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds(int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration.WithMessageLockDurationInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageLockDurationInSeconds (durationInSeconds As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageLockDurationInSeconds : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageLockDuration.WithMessageLockDurationInSeconds durationInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInSeconds">秒単位で設定したロックの期間です。</param>
        <summary>
            他の受信者に対してメッセージをロックする時間を指定します。
            注: は明示的にオーバーライドしない限り、既定のロック期間は 60 秒、最大許容値 300 秒です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプション定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>