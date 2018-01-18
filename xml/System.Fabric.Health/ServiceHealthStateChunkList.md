<Type Name="ServiceHealthStateChunkList" FullName="System.Fabric.Health.ServiceHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ServiceHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.ServiceHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of ServiceHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;ServiceHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ServiceHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.ServiceHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="49bc5-101">含むリストを表す<see cref="T:System.Fabric.Health.ServiceHealthStateChunk" />項目。</span><span class="sxs-lookup"><span data-stu-id="49bc5-101">Represents a list that contains <see cref="T:System.Fabric.Health.ServiceHealthStateChunk" /> items.</span></span>
            </summary>
    <remarks><span data-ttu-id="49bc5-102">一覧は、ヘルス状態のチャンク クエリを通じて取得できます。</span><span class="sxs-lookup"><span data-stu-id="49bc5-102">The list can be obtained through health state chunk queries.</span></span> <span data-ttu-id="49bc5-103">クエリは、メッセージを格納できる以上のチャンクを結果として必要があります。</span><span class="sxs-lookup"><span data-stu-id="49bc5-103">The queries may have as result more chunks that can fit a message.</span></span>
            <span data-ttu-id="49bc5-104">この場合、メッセージに一致する項目の一覧が返されます、合計項目の数を示すカウントを利用できます。</span><span class="sxs-lookup"><span data-stu-id="49bc5-104">In this case, the list of items that fit the message is returned plus a count that shows how many total items are available.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49bc5-105">空のインスタンスを作成<see cref="T:System.Fabric.Health.ServiceHealthStateChunkList" />です。</span><span class="sxs-lookup"><span data-stu-id="49bc5-105">Instantiates an empty <see cref="T:System.Fabric.Health.ServiceHealthStateChunkList" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>