<Type Name="DeployedApplicationHealthStateChunkList" FullName="System.Fabric.Health.DeployedApplicationHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.DeployedApplicationHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.DeployedApplicationHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of DeployedApplicationHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;DeployedApplicationHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.DeployedApplicationHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.DeployedApplicationHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25e40-101">含むリストを表す<see cref="T:System.Fabric.Health.DeployedApplicationHealthStateChunk" />項目。</span><span class="sxs-lookup"><span data-stu-id="25e40-101">Represents a list that contains <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateChunk" /> items.</span></span>
            </summary>
    <remarks><span data-ttu-id="25e40-102">一覧は、ヘルス状態のチャンク クエリを通じて取得できます。</span><span class="sxs-lookup"><span data-stu-id="25e40-102">The list can be obtained through health state chunk queries.</span></span> <span data-ttu-id="25e40-103">クエリは、メッセージを格納できる以上のチャンクを結果として必要があります。</span><span class="sxs-lookup"><span data-stu-id="25e40-103">The queries may have as result more chunks that can fit a message.</span></span>
            <span data-ttu-id="25e40-104">この場合、メッセージに一致する項目の一覧が返されます、合計項目の数を示すカウントを利用できます。</span><span class="sxs-lookup"><span data-stu-id="25e40-104">In this case, the list of items that fit the message is returned plus a count that shows how many total items are available.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25e40-105">空のインスタンスを作成<see cref="T:System.Fabric.Health.DeployedApplicationHealthStateChunkList" />です。</span><span class="sxs-lookup"><span data-stu-id="25e40-105">Instantiates an empty <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateChunkList" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>