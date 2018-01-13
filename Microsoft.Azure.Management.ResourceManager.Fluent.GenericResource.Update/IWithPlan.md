<Type Name="IWithPlan" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan">
  <TypeSignature Language="C#" Value="public interface IWithPlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPlan" />
  <TypeSignature Language="F#" Value="type IWithPlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6bf51-101">リソース プランを変更できるように、汎用リソース更新します。</span><span class="sxs-lookup"><span data-stu-id="6bf51-101">A generic resource update allowing to change the resource plan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithoutPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithoutPlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan.WithoutPlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPlan : unit -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate" Usage="iWithPlan.WithoutPlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6bf51-102">リソースのプランを指定します。</span><span class="sxs-lookup"><span data-stu-id="6bf51-102">Specifies the plan of the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="6bf51-103">汎用リソース更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="6bf51-103">the next stage of the generic resource update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithPlan (string name, string publisher, string product, string promotionCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithPlan(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan.WithPlan(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlan (name As String, publisher As String, product As String, promotionCode As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPlan : string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate" Usage="iWithPlan.WithPlan (name, publisher, product, promotionCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6bf51-104">プランを名前します。</span><span class="sxs-lookup"><span data-stu-id="6bf51-104">name the name of the plan</span></span></param>
        <param name="publisher"><span data-ttu-id="6bf51-105">計画の発行元のパブリッシャー</span><span class="sxs-lookup"><span data-stu-id="6bf51-105">publisher the publisher of the plan</span></span></param>
        <param name="product"><span data-ttu-id="6bf51-106">製品の製品名</span><span class="sxs-lookup"><span data-stu-id="6bf51-106">product the name of the product</span></span></param>
        <param name="promotionCode"><span data-ttu-id="6bf51-107">promotionCode 存在する場合、プロモーション コード</span><span class="sxs-lookup"><span data-stu-id="6bf51-107">promotionCode the promotion code, if any</span></span></param>
        <summary>
            <span data-ttu-id="6bf51-108">リソースのプランを指定します。</span><span class="sxs-lookup"><span data-stu-id="6bf51-108">Specifies the plan of the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="6bf51-109">汎用リソース更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="6bf51-109">the next stage of the generic resource update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>