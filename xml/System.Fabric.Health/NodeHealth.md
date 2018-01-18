<Type Name="NodeHealth" FullName="System.Fabric.Health.NodeHealth">
  <TypeSignature Language="C#" Value="public sealed class NodeHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type NodeHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="76d1b-101">によって返されるノードの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="76d1b-101">Describes the health of a node as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealth.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.NodeHealth.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76d1b-102">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="76d1b-102">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76d1b-103">ノード名。</span><span class="sxs-lookup"><span data-stu-id="76d1b-103">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealth.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76d1b-104">文字列表現を取得、<see cref="T:System.Fabric.Health.NodeHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="76d1b-104">Gets a string representation of the <see cref="T:System.Fabric.Health.NodeHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="76d1b-105"><see cref="T:System.Fabric.Health.NodeHealth" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="76d1b-105">A string representation of the <see cref="T:System.Fabric.Health.NodeHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>