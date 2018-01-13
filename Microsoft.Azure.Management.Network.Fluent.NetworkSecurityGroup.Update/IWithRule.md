<Type Name="IWithRule" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule">
  <TypeSignature Language="C#" Value="public interface IWithRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRule" />
  <TypeSignature Language="F#" Value="type IWithRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17919-101">追加またはセキュリティの規則の削除を許可するリソース定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="17919-101">The stage of the resource definition allowing to add or remove security rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt; DefineRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt; DefineRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.DefineRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" Usage="iWithRule.DefineRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="17919-102">新しいセキュリティ規則の名前。</span><span class="sxs-lookup"><span data-stu-id="17919-102">The name of the new security rule.</span></span></param>
        <summary>
            <span data-ttu-id="17919-103">このネットワーク セキュリティ グループに追加する新しいセキュリティ ルールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="17919-103">Begins the definition of a new security rule to be added to this network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="17919-104">新しいセキュリティ ルールの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="17919-104">The first stage of the new security rule definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate UpdateRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate UpdateRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.UpdateRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithRule.UpdateRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="17919-105">既存のセキュリティ規則の名前。</span><span class="sxs-lookup"><span data-stu-id="17919-105">The name of an existing security rule.</span></span></param>
        <summary>
            <span data-ttu-id="17919-106">このネットワーク セキュリティ グループの既存のセキュリティ ルールの更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="17919-106">Begins the description of an update of an existing security rule of this network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="17919-107">セキュリティ ルールの更新プログラムの説明の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="17919-107">The first stage of the security rule update description.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate WithoutRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate WithoutRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.WithoutRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate" Usage="iWithRule.WithoutRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="17919-108">削除するセキュリティの規則の名前。</span><span class="sxs-lookup"><span data-stu-id="17919-108">The name of the security rule to remove.</span></span></param>
        <summary>
            <span data-ttu-id="17919-109">既存のセキュリティ規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="17919-109">Removes an existing security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="17919-110">ネットワーク セキュリティ グループの説明の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="17919-110">The next stage of the network security group description.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>