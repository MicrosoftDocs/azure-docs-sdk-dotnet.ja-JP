<Type Name="Plan" FullName="Microsoft.Azure.Management.Compute.Models.Plan">
  <TypeSignature Language="C#" Value="public class Plan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Plan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Plan" />
  <TypeSignature Language="VB.NET" Value="Public Class Plan" />
  <TypeSignature Language="F#" Value="type Plan = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。 この要素は marketplace イメージのみ使用されます。
            API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。  Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&gt;**です。 必要な情報を入力し、クリックして**保存**です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor" />
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
            Plan クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan (string name = null, string publisher = null, string product = null, string promotionCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional publisher As String = null, Optional product As String = null, Optional promotionCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Plan : string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Plan" Usage="new Microsoft.Azure.Management.Compute.Models.Plan (name, publisher, product, promotionCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">プランの ID</param>
        <param name="publisher">パブリッシャーの id。</param>
        <param name="product">Marketplace からのイメージの製品を指定します。 これは、imageReference 要素の下のプランと同じ値です。</param>
        <param name="promotionCode">販売促進コード。</param>
        <summary>
            Plan クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または設定、プランの id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、marketplace からのイメージの製品を指定します。 これは、imageReference 要素の下のプランと同じ値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromotionCode">
      <MemberSignature Language="C#" Value="public string PromotionCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PromotionCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberSignature Language="VB.NET" Value="Public Property PromotionCode As String" />
      <MemberSignature Language="F#" Value="member this.PromotionCode : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="promotionCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプロモーション コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
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
            取得または設定、パブリッシャーの id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>