<Type Name="GetPropertyOperation" FullName="System.Fabric.GetPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class GetPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GetPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type GetPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="47581-101">表す、<see cref="T:System.Fabric.PropertyBatchOperation" />にある場合、指定したプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="47581-101">Represents a <see cref="T:System.Fabric.PropertyBatchOperation" /> that gets the specified property if it exists.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="47581-102">注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗バッチ全体が失敗し、コミットできません。</span><span class="sxs-lookup"><span data-stu-id="47581-102">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch will fail and not be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation propertyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="47581-103">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="47581-103">The name of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="47581-104">新しいインスタンスをインスタンス化、<see cref="T:System.Fabric.GetPropertyOperation" />指定したプロパティ名を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="47581-104">Instantiates a new instance of the <see cref="T:System.Fabric.GetPropertyOperation" /> class with specified property name.</span></span></para>
        </summary>
        <remarks>
          <para>
            <span data-ttu-id="47581-105"><see cref="P:System.Fabric.GetPropertyOperation.IncludeValue" />設定されている<languageKeyword>true</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="47581-105"><see cref="P:System.Fabric.GetPropertyOperation.IncludeValue" /> is set to <languageKeyword>true</languageKeyword>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName, bool includeValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, bool includeValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, includeValue As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string * bool -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation (propertyName, includeValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="includeValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="47581-106">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="47581-106">The name of the property.</span></span></para>
        </param>
        <param name="includeValue">
          <para><span data-ttu-id="47581-107">戻り値に値を含める必要がありますまたはメタデータのみを返す必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="47581-107">Specifies whether values should be included in the return or only metadata should be returned.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="47581-108">新しいインスタンスを初期化、 <see cref="T:System.Fabric.GetPropertyOperation" /> with プロパティ名を指定し、値のフラグが含まれています。</span><span class="sxs-lookup"><span data-stu-id="47581-108">Initializes a new instance of the <see cref="T:System.Fabric.GetPropertyOperation" /> with specified property name and include value flag.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeValue">
      <MemberSignature Language="C#" Value="public bool IncludeValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludeValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeValue : bool" Usage="System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="47581-109">プロパティの値が、メタデータと共に返されるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="47581-109">Gets a value indicating whether the value of the property is returned together with the metadata.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="47581-110"><languageKeyword>true</languageKeyword>プロパティの値を含める必要がある場合<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="47581-110"><languageKeyword>true</languageKeyword> if the value of the property should be included; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>