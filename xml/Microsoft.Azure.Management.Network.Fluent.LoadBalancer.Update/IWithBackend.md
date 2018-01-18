<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ead76-101">ロード バランサーのステージでは、追加またはバックエンドを削除する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="ead76-101">The stage of the load balancer update allowing to add or remove backends.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.DefineBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackend (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithBackend.DefineBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ead76-102">新しいバックエンドの名前。</span><span class="sxs-lookup"><span data-stu-id="ead76-102">The name for the new backend.</span></span></param>
        <summary>
            <span data-ttu-id="ead76-103">このロード バランサーの更新プログラムの一部として、新しいバックエンドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="ead76-103">Begins the definition of a new backend as part of this load balancer update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ead76-104">バックエンドの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="ead76-104">The first stage of the backend definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate UpdateBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate UpdateBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.UpdateBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate" Usage="iWithBackend.UpdateBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ead76-105">更新するバックエンドの名前。</span><span class="sxs-lookup"><span data-stu-id="ead76-105">The name of the backend to update.</span></span></param>
        <summary>
            <span data-ttu-id="ead76-106">このロード バランサーの既存のバックエンドを更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="ead76-106">Begins the description of an update to an existing backend of this load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ead76-107">更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="ead76-107">The first stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.WithoutBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithBackend.WithoutBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ead76-108">削除するバックエンドの名前です。</span><span class="sxs-lookup"><span data-stu-id="ead76-108">The name of the backend to remove.</span></span></param>
        <summary>
            <span data-ttu-id="ead76-109">ロード バランサーから、指定されたバックエンドを削除します。</span><span class="sxs-lookup"><span data-stu-id="ead76-109">Removes the specified backend from the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ead76-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ead76-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>