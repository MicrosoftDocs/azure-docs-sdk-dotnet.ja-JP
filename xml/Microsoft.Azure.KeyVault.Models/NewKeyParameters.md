<Type Name="NewKeyParameters" FullName="Microsoft.Azure.KeyVault.Models.NewKeyParameters">
  <TypeSignature Language="C#" Value="public class NewKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NewKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.NewKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class NewKeyParameters" />
  <TypeSignature Language="F#" Value="type NewKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aafa7-101">新しい暗号化キーの作成に使用されるパラメーターをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-101">Describes parameters used for creation of a new cryptographic key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NewKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.NewKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.KeyAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.KeyAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As KeyAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.KeyAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.KeyAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-102">取得または目的のキー管理の属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-102">Gets or sets the desired key management attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurveName">
      <MemberSignature Language="C#" Value="public string CurveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.CurveName" />
      <MemberSignature Language="VB.NET" Value="Public Property CurveName As String" />
      <MemberSignature Language="F#" Value="member this.CurveName : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.CurveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-103">取得または楕円曲線暗号 (ECC) のアルゴリズムでは使用を目的の曲線の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-103">Gets or sets the name of desired curve for used with Elliptic Curve Cryptography (ECC) algorithms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyOps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeyOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeyOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.KeyOps" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyOps As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeyOps : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.KeyOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-104">取得またはキーをサポートする目的の操作を設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-104">Gets or sets the desired operations that the key will support.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-105">取得または目的のキー サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-105">Gets or sets the desired key size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.Kty" />
      <MemberSignature Language="VB.NET" Value="Public Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-106">取得または目的の JsonWebKey キーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-106">Gets or sets the desired JsonWebKey key type.</span></span> <span data-ttu-id="aafa7-107">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="aafa7-107">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.NewKeyParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.NewKeyParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aafa7-108">取得またはキー/値ペアの形式でアプリケーション固有のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="aafa7-108">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>