<Type Name="MetadataItem" FullName="Microsoft.Azure.Batch.MetadataItem">
  <TypeSignature Language="C#" Value="public class MetadataItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetadataItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.MetadataItem" />
  <TypeSignature Language="VB.NET" Value="Public Class MetadataItem" />
  <TypeSignature Language="F#" Value="type MetadataItem = class&#xA;    interface ITransportObjectProvider&lt;MetadataItem&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="75206-101">バッチ サービスのリソースに関連付けられている名前と値のペア。</span><span class="sxs-lookup"><span data-stu-id="75206-101">A name-value pair associated with a Batch service resource.</span></span> <span data-ttu-id="75206-102">バッチ サービスはこのメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="75206-102">The Batch service does not assign any meaning to this metadata; it is solely for the use of user code.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetadataItem (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.MetadataItem.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.MetadataItem : string * string -&gt; Microsoft.Azure.Batch.MetadataItem" Usage="new Microsoft.Azure.Batch.MetadataItem (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="75206-103"><see cref="T:Microsoft.Azure.Batch.MetadataItem" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="75206-103">The name of the <see cref="T:Microsoft.Azure.Batch.MetadataItem" />.</span></span></param>
        <param name="value"><span data-ttu-id="75206-104"><see cref="T:Microsoft.Azure.Batch.MetadataItem" /> の値。</span><span class="sxs-lookup"><span data-stu-id="75206-104">The value of the <see cref="T:Microsoft.Azure.Batch.MetadataItem" />.</span></span></param>
        <summary>
            <span data-ttu-id="75206-105"><see cref="T:Microsoft.Azure.Batch.MetadataItem" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="75206-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.MetadataItem" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MetadataItem.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.MetadataItem.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75206-106"><see cref="T:Microsoft.Azure.Batch.MetadataItem" /> の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="75206-106">Gets the name of the <see cref="T:Microsoft.Azure.Batch.MetadataItem" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MetadataItem.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="Microsoft.Azure.Batch.MetadataItem.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75206-107"><see cref="T:Microsoft.Azure.Batch.MetadataItem" /> の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="75206-107">Gets the value of the <see cref="T:Microsoft.Azure.Batch.MetadataItem" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>