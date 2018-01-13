<Type Name="IWithSize" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSize">
  <TypeSignature Language="C#" Value="public interface IWithSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSize" />
  <TypeSignature Language="F#" Value="type IWithSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="21318-101">サイズを指定できるようにトピックの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="21318-101">The stage of the topic definition allowing to specify size.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSizeInMB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithSizeInMB (long sizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithSizeInMB(int64 sizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSize.WithSizeInMB(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInMB (sizeInMB As Long) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInMB : int64 -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithSize.WithSizeInMB sizeInMB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInMB" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sizeInMB"><span data-ttu-id="21318-102">サイズ (mb)。</span><span class="sxs-lookup"><span data-stu-id="21318-102">Size in MB.</span></span></param>
        <summary>
            <span data-ttu-id="21318-103">トピックに割り当てられたメモリの最大サイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="21318-103">Specifies the maximum size of memory allocated for the topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="21318-104">トピックの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="21318-104">The next stage of topic definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>