<Type Name="IWithPlan" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan">
  <TypeSignature Language="C#" Value="public interface IWithPlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPlan" />
  <TypeSignature Language="F#" Value="type IWithPlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b37d5-101">購入プランを指定するように、仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="b37d5-101">The stage of a virtual machine definition allowing to specify a purchase plan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithPlan (Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan plan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithPlan(class Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan plan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan.WithPlan(Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlan (plan As PurchasePlan) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPlan : Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithPlan.WithPlan plan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan" />
      </Parameters>
      <Docs>
        <param name="plan"><span data-ttu-id="b37d5-102">購入プランです。</span><span class="sxs-lookup"><span data-stu-id="b37d5-102">A purchase plan.</span></span></param>
        <summary>
            <span data-ttu-id="b37d5-103">仮想マシンの購入プランを指定します。</span><span class="sxs-lookup"><span data-stu-id="b37d5-103">Specifies the purchase plan for the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b37d5-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b37d5-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPromotionalPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithPromotionalPlan (Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan plan, string promotionCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithPromotionalPlan(class Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan plan, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan.WithPromotionalPlan(Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPromotionalPlan (plan As PurchasePlan, promotionCode As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPromotionalPlan : Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithPlan.WithPromotionalPlan (plan, promotionCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="plan"><span data-ttu-id="b37d5-105">購入プランです。</span><span class="sxs-lookup"><span data-stu-id="b37d5-105">A purchase plan.</span></span></param>
        <param name="promotionCode"><span data-ttu-id="b37d5-106">プロモーション コード。</span><span class="sxs-lookup"><span data-stu-id="b37d5-106">A promotion code.</span></span></param>
        <summary>
            <span data-ttu-id="b37d5-107">仮想マシンの購入プランを指定します。</span><span class="sxs-lookup"><span data-stu-id="b37d5-107">Specifies the purchase plan for the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b37d5-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b37d5-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>