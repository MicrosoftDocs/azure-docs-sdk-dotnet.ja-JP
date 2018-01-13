<Type Name="ImageReference" FullName="Microsoft.Azure.Management.Compute.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ImageReference = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            使用するイメージに関する情報を指定します。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージに関する情報を指定することができます。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージを使用するが、その他の作成操作で使用されていない場合、この要素が必要です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ImageReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string id = null, string publisher = null, string offer = null, string sku = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string publisher, string offer, string sku, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ImageReference" Usage="new Microsoft.Azure.Management.Compute.Models.ImageReference (id, publisher, offer, sku, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="publisher">イメージのパブリッシャーです。</param>
        <param name="offer">プラットフォーム イメージまたは仮想マシンの作成に使用される marketplace イメージのオファーを指定します。</param>
        <param name="sku">イメージの SKU。</param>
        <param name="version">プラットフォーム イメージまたは仮想マシンの作成に使用される marketplace イメージのバージョンを指定します。 許可されている形式は、Major.Minor.Build または '最新' です。 メジャー、マイナー、ビルドは 10 進数とします。 指定して '最新' で使用できるイメージの最新バージョンを使用する時間を展開します。 使用する場合でも '最新'、VM イメージは自動的に更新した後は、新しいバージョンが利用可能な場合でも時間を展開します。</param>
        <summary>
            ImageReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、プラットフォーム イメージまたは仮想マシンの作成に使用される marketplace イメージのオファーを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイメージのパブリッシャーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイメージの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、プラットフォーム イメージまたは仮想マシンの作成に使用される marketplace イメージのバージョンを指定します。 許可されている形式は、Major.Minor.Build または '最新' です。 メジャー、マイナー、ビルドは 10 進数とします。 指定して '最新' で使用できるイメージの最新バージョンを使用する時間を展開します。 使用する場合でも '最新'、VM イメージは自動的に更新した後は、新しいバージョンが利用可能な場合でも時間を展開します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>