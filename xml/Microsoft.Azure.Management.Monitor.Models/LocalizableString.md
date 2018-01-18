<Type Name="LocalizableString" FullName="Microsoft.Azure.Management.Monitor.Models.LocalizableString">
  <TypeSignature Language="C#" Value="public class LocalizableString" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocalizableString extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
  <TypeSignature Language="VB.NET" Value="Public Class LocalizableString" />
  <TypeSignature Language="F#" Value="type LocalizableString = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a08c1-101">ローカライズ可能な文字列のクラス。</span><span class="sxs-lookup"><span data-stu-id="a08c1-101">The localizable string class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalizableString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.LocalizableString.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a08c1-102">ローカライズ可能な文字列クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a08c1-102">Initializes a new instance of the LocalizableString class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalizableString (string value, string localizedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, string localizedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.LocalizableString.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As String, Optional localizedValue As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.LocalizableString : string * string -&gt; Microsoft.Azure.Management.Monitor.Models.LocalizableString" Usage="new Microsoft.Azure.Management.Monitor.Models.LocalizableString (value, localizedValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="localizedValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="a08c1-103">invariant 値。</span><span class="sxs-lookup"><span data-stu-id="a08c1-103">the invariant value.</span></span></param>
        <param name="localizedValue"><span data-ttu-id="a08c1-104">ロケール固有の値。</span><span class="sxs-lookup"><span data-stu-id="a08c1-104">the locale specific value.</span></span></param>
        <summary>
            <span data-ttu-id="a08c1-105">ローカライズ可能な文字列クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a08c1-105">Initializes a new instance of the LocalizableString class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalizedValue">
      <MemberSignature Language="C#" Value="public string LocalizedValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalizedValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.LocalizableString.LocalizedValue" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalizedValue As String" />
      <MemberSignature Language="F#" Value="member this.LocalizedValue : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.LocalizableString.LocalizedValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localizedValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a08c1-106">取得またはロケールの特定の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a08c1-106">Gets or sets the locale specific value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.LocalizableString.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="localizableString.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a08c1-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a08c1-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a08c1-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a08c1-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.LocalizableString.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.LocalizableString.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a08c1-109">取得または invariant 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a08c1-109">Gets or sets the invariant value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>