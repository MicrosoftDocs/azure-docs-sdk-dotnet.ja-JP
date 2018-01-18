<Type Name="ApplicationHealthPolicyMap" FullName="System.Fabric.Health.ApplicationHealthPolicyMap">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthPolicyMap : System.Collections.Generic.Dictionary&lt;Uri,System.Fabric.Health.ApplicationHealthPolicy&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthPolicyMap extends System.Collections.Generic.Dictionary`2&lt;class System.Uri, class System.Fabric.Health.ApplicationHealthPolicy&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthPolicyMap" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthPolicyMap&#xA;Inherits Dictionary(Of Uri, ApplicationHealthPolicy)" />
  <TypeSignature Language="F#" Value="type ApplicationHealthPolicyMap = class&#xA;    inherit Dictionary&lt;Uri, ApplicationHealthPolicy&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.Uri,System.Fabric.Health.ApplicationHealthPolicy&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Uri</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Fabric.Health.ApplicationHealthPolicy</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="38ec8-101">別のアプリケーションの特定のアプリケーションの正常性ポリシーを含むマップを表します。</span><span class="sxs-lookup"><span data-stu-id="38ec8-101">Represents a map that contains specific application health policies for different applications.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="38ec8-102">ようなクエリで使用できる<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />または<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription)" />をアプリケーションの評価方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="38ec8-102">Can be used by queries like <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> or <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription)" /> to determine how the applications are evaluated.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthPolicyMap ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicyMap.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38ec8-103"><see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38ec8-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicyMap.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthPolicyMap.ToString " />
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
            <span data-ttu-id="38ec8-104">文字列表現を取得、<see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" />です。</span><span class="sxs-lookup"><span data-stu-id="38ec8-104">Gets a string representation of the <see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" />.</span></span>
            </summary>
        <returns><span data-ttu-id="38ec8-105"><see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="38ec8-105">A string representation of the <see cref="T:System.Fabric.Health.ApplicationHealthPolicyMap" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>