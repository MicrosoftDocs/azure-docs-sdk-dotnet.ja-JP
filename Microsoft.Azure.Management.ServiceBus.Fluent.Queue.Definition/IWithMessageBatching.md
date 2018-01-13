<Type Name="IWithMessageBatching" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageBatching">
  <TypeSignature Language="C#" Value="public interface IWithMessageBatching" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageBatching" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageBatching" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageBatching" />
  <TypeSignature Language="F#" Value="type IWithMessageBatching = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            許可するキューの定義のステージでは、バッチ処理の動作を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithoutMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithoutMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageBatching.WithoutMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMessageBatching () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithMessageBatching.WithoutMessageBatching " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既定のバッチ処理を無効にするこのキューでを指定します。
            Service Bus をバッチ処理バッチを実行できます複数のメッセージを記述または内部ストアからメッセージを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>