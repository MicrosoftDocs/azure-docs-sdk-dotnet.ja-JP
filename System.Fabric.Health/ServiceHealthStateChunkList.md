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
            含むリストを表す<see cref="T:System.Fabric.Health.ServiceHealthStateChunk" />項目。
            </summary>
    <remarks>一覧は、ヘルス状態のチャンク クエリを通じて取得できます。 クエリは、メッセージを格納できる以上のチャンクを結果として必要があります。
            この場合、メッセージに一致する項目の一覧が返されます、合計項目の数を示すカウントを利用できます。</remarks>
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
            空のインスタンスを作成<see cref="T:System.Fabric.Health.ServiceHealthStateChunkList" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>