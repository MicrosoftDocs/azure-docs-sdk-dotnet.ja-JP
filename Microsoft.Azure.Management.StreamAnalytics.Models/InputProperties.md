<Type Name="InputProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties">
  <TypeSignature Language="C#" Value="public class InputProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InputProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class InputProperties" />
  <TypeSignature Language="F#" Value="type InputProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            入力に関連付けられているプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            InputProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties (Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor(Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties (serialization, diagnostics, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serialization">入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。
            PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="diagnostics">顧客のアテンションを正当化する、入力、出力、または、全体的なジョブに適用可能な条件について説明します。</param>
        <param name="etag">入力の現在のエンティティ タグ。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</param>
        <summary>
            InputProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As Diagnostics" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            顧客の注意を保証する取得は、入力、出力、または、ジョブ全体に適用可能な状態を説明します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            入力の現在のエンティティ タグを取得します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberSignature Language="VB.NET" Value="Public Property Serialization As Serialization" />
      <MemberSignature Language="F#" Value="member this.Serialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>