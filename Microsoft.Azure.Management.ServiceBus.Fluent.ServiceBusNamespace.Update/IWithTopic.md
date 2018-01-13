<Type Name="IWithTopic" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithTopic">
  <TypeSignature Language="C#" Value="public interface IWithTopic" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTopic" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithTopic" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTopic" />
  <TypeSignature Language="F#" Value="type IWithTopic = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Service Bus 名前空間の更新を許可する、名前空間のトピックを管理するの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewTopic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithNewTopic (string name, int maxSizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithNewTopic(string name, int32 maxSizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithTopic.WithNewTopic(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewTopic (name As String, maxSizeInMB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewTopic : string * int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate" Usage="iWithTopic.WithNewTopic (name, maxSizeInMB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxSizeInMB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">トピックの名前です。</param>
        <param name="maxSizeInMB">トピック エンティティに割り当てられたメモリの最大サイズ。</param>
        <summary>
            Service Bus 名前空間にトピック エンティティを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Service Bus 名前空間の更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutTopic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithoutTopic (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithoutTopic(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithTopic.WithoutTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTopic (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTopic : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate" Usage="iWithTopic.WithoutTopic name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">トピックの名前です。</param>
        <summary>
            Service Bus 名前空間からトピック エンティティを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Service Bus 名前空間の更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>