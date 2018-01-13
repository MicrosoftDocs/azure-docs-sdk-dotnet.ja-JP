<Type Name="ApplicationTypePagedList" FullName="System.Fabric.Query.ApplicationTypePagedList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypePagedList : System.Fabric.Query.PagedList&lt;System.Fabric.Query.ApplicationType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypePagedList extends System.Fabric.Query.PagedList`1&lt;class System.Fabric.Query.ApplicationType&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationTypePagedList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypePagedList&#xA;Inherits PagedList(Of ApplicationType)" />
  <TypeSignature Language="F#" Value="type ApplicationTypePagedList = class&#xA;    inherit PagedList&lt;ApplicationType&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.PagedList&lt;System.Fabric.Query.ApplicationType&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Query.ApplicationType</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>1 つのページを表す<see cref="T:System.Fabric.Query.ApplicationType" />呼び出すことによって取得<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。 ページの一覧で構成されている、返される結果の後続のページにアクセスするために使用できる継続トークンと共に (リスト) を保持します。</para>
    </summary>
    <remarks>
      <para>
                    後続のページがある場合は、それにアクセスするこのオブジェクトに渡された継続トークンを使用できます。
                    継続トークンの使用手順については、次を参照してください。<see cref="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />です。
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationTypePagedList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypePagedList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            空のページを作成<see cref="T:System.Fabric.Query.ApplicationType" /> ボックスの一覧です。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>