<Type Name="IWithSubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSubscription">
  <TypeSignature Language="C#" Value="public interface IWithSubscription" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubscription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubscription" />
  <TypeSignature Language="F#" Value="type IWithSubscription = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Service Bus 名前空間の更新を許可するトピックのサブスクリプションを管理するの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewSubscription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewSubscription(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSubscription.WithNewSubscription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSubscription (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSubscription : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithSubscription.WithNewSubscription name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">キューの名前です。</param>
        <summary>
            Service Bus トピックのサブスクリプションのエンティティを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Service Bus トピックの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutSubscription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutSubscription(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSubscription.WithoutSubscription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSubscription (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSubscription : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithSubscription.WithoutSubscription name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">サブスクリプションの名前。</param>
        <summary>
            Service Bus トピックに関連付けられているサブスクリプション エンティティを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Service Bus トピックの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>