<Type Name="Sku" FullName="Microsoft.Azure.Management.Redis.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SKU のパラメーターは、作成する Redis 操作を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Sku (string name, string family, int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string family, int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.Sku.#ctor(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, family As String, capacity As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.Sku : string * string * int -&gt; Microsoft.Azure.Management.Redis.Models.Sku" Usage="new Microsoft.Azure.Management.Redis.Models.Sku (name, family, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">Redis キャッシュによる展開の種類。 有効な値: (Basic、Standard、Premium)。 使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</param>
        <param name="family">使用する SKU ファミリ。 有効な値: (C、P)。
            (C Basic/standard、P を = = Premium)。 使用可能な値が含まれます: 'C'、'P'</param>
        <param name="capacity">展開する Redis キャッシュのサイズ。 有効な値: C (Basic/standard) ファミリ (0、1、2、3、4、5、6)、P (Premium) ファミリ (1、2、3、4)。</param>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public int Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.Sku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Integer" />
      <MemberSignature Language="F#" Value="member this.Capacity : int with get, set" Usage="Microsoft.Azure.Management.Redis.Models.Sku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または展開する Redis キャッシュのサイズを設定します。 有効な値: C (Basic/standard) ファミリ (0、1、2、3、4、5、6)、P (Premium) ファミリ (1、2、3、4)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.Sku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.Sku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            取得または使用する SKU ファミリを設定します。 有効な値: (C、P)。 (C Basic/standard、P を = = Premium)。 使用可能な値が含まれます: 'C'、'P'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を展開する Redis キャッシュの種類。 有効な値: (Basic、Standard、Premium)。 使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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