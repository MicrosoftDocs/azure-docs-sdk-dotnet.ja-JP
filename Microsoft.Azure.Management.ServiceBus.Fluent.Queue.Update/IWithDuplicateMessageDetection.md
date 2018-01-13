<Type Name="IWithDuplicateMessageDetection" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection">
  <TypeSignature Language="C#" Value="public interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDuplicateMessageDetection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="F#" Value="type IWithDuplicateMessageDetection = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            重複メッセージ検出の履歴の期間を指定するように、キューの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDuplicateMessageDetectionHistoryDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithDuplicateMessageDetectionHistoryDuration (TimeSpan duration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithDuplicateMessageDetectionHistoryDuration(valuetype System.TimeSpan duration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection.WithDuplicateMessageDetectionHistoryDuration(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDuplicateMessageDetectionHistoryDuration (duration As TimeSpan) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDuplicateMessageDetectionHistoryDuration : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithDuplicateMessageDetection.WithDuplicateMessageDetectionHistoryDuration duration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duration">履歴の期間です。</param>
        <summary>
            重複メッセージ検出の履歴の期間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDuplicateMessageDetection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutDuplicateMessageDetection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutDuplicateMessageDetection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection.WithoutDuplicateMessageDetection" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDuplicateMessageDetection () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDuplicateMessageDetection : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithDuplicateMessageDetection.WithoutDuplicateMessageDetection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            重複するメッセージを指定します。 検出を無効にする必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>