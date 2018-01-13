<Type Name="IWithSize" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSize">
  <TypeSignature Language="C#" Value="public interface IWithSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSize" />
  <TypeSignature Language="F#" Value="type IWithSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サイズを指定できるようにトピックの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSizeInMB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithSizeInMB (long sizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithSizeInMB(int64 sizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithSize.WithSizeInMB(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInMB (sizeInMB As Long) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInMB : int64 -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithSize.WithSizeInMB sizeInMB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInMB" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sizeInMB">サイズ (mb)。</param>
        <summary>
            トピックに割り当てられたメモリの最大サイズを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>トピックの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>