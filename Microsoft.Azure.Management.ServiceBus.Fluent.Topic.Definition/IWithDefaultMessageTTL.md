<Type Name="IWithDefaultMessageTTL" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL">
  <TypeSignature Language="C#" Value="public interface IWithDefaultMessageTTL" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDefaultMessageTTL" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDefaultMessageTTL" />
  <TypeSignature Language="F#" Value="type IWithDefaultMessageTTL = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            メッセージの TTL の既定値を定義できるようにトピックの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDefaultMessageTTL">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDefaultMessageTTL (TimeSpan ttl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDefaultMessageTTL(valuetype System.TimeSpan ttl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL.WithDefaultMessageTTL(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultMessageTTL (ttl As TimeSpan) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultMessageTTL : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithDefaultMessageTTL.WithDefaultMessageTTL ttl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttl" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="ttl">ライブの期間を時間です。</param>
        <summary>
            メッセージが切れるまでの期間を指定します。
            注: これが明示的にオーバーライドされない限り、既定の ttl は無期限 (TimeSpan.Max)。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>トピックの定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>