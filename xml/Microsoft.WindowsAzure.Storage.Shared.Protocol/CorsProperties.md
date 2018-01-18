<Type Name="CorsProperties" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties">
  <TypeSignature Language="C#" Value="public sealed class CorsProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorsProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorsProperties" />
  <TypeSignature Language="F#" Value="type CorsProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14451-101">CORS に関連するサービスのプロパティを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="14451-101">Class representing the service properties pertaining to CORS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14451-102">CORS のプロパティ オブジェクトを構築します。</span><span class="sxs-lookup"><span data-stu-id="14451-102">Constructs a CORS Properties object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorsRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule&gt; CorsRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule&gt; CorsRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties.CorsRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CorsRules As IList(Of CorsRule)" />
      <MemberSignature Language="F#" Value="member this.CorsRules : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties.CorsRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14451-103">取得または CORS ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="14451-103">Gets or sets CORS rules.</span></span> <span data-ttu-id="14451-104">一覧の順序は、ルールの優先順位に対応します。</span><span class="sxs-lookup"><span data-stu-id="14451-104">The order of the list corresponds to precedence of rules.</span></span> 
            </summary>
        <value><span data-ttu-id="14451-105">最大 5 個の CORS ルールを含むコレクション。</span><span class="sxs-lookup"><span data-stu-id="14451-105">A collection containing CORS rules, limited to 5.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>