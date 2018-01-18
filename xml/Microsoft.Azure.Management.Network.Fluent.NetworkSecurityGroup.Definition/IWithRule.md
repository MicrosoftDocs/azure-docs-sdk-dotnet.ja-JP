<Type Name="IWithRule" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule">
  <TypeSignature Language="C#" Value="public interface IWithRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRule" />
  <TypeSignature Language="F#" Value="type IWithRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95877-101">新しいセキュリティ規則を定義できるように段階です。</span><span class="sxs-lookup"><span data-stu-id="95877-101">The stage allowing to define a new security rule.</span></span>
            <span data-ttu-id="95877-102">セキュリティ規則の説明が十分に完了すると、このネットワーク セキュリティ グループにアタッチする Attachable.attach() を使用します。</span><span class="sxs-lookup"><span data-stu-id="95877-102">When the security rule description is complete enough, use  Attachable.attach() to attach it to this network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt; DefineRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt; DefineRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule.DefineRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRule (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt;" Usage="iWithRule.DefineRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="95877-103">新しいセキュリティ ルールの名前です。</span><span class="sxs-lookup"><span data-stu-id="95877-103">The name for the new security rule.</span></span></param>
        <summary>
            <span data-ttu-id="95877-104">新しいセキュリティ ルールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="95877-104">Starts the definition of a new security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="95877-105">セキュリティ ルールの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="95877-105">The first stage of the security rule definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>