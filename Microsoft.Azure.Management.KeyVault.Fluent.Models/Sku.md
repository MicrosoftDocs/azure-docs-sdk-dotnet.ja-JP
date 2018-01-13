<Type Name="Sku" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SKU の詳細
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.#ctor(Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku : Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName" />
      </Parameters>
      <Docs>
        <param name="name">Key vault が標準的な資格情報コンテナーまたは premium のコンテナーかどうかを指定する SKU の名前です。 使用可能な値が含まれます: 'standard'、'premium'</param>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public static string Family { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SKU ファミリ名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、key vault が標準的な資格情報コンテナーまたは premium のコンテナーかどうかを指定する SKU 名を設定します。 使用可能な値が含まれます: 'standard'、'premium'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>