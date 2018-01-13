<Type Name="KeySignParameters" FullName="Microsoft.Azure.KeyVault.Models.KeySignParameters">
  <TypeSignature Language="C#" Value="public class KeySignParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeySignParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeySignParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class KeySignParameters" />
  <TypeSignature Language="F#" Value="type KeySignParameters = class" />
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
            キーの操作のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeySignParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            KeySignParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeySignParameters (string algorithm, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string algorithm, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (algorithm As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeySignParameters : string * byte[] -&gt; Microsoft.Azure.KeyVault.Models.KeySignParameters" Usage="new Microsoft.Azure.KeyVault.Models.KeySignParameters (algorithm, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="algorithm">署名/検証アルゴリズムの識別子です。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</param>
        <param name="value">To be added.</param>
        <summary>
            KeySignParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeySignParameters.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeySignParameters.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="alg")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または署名/検証アルゴリズム識別子を設定します。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeySignParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keySignParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public byte[] Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeySignParameters.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Byte()" />
      <MemberSignature Language="F#" Value="member this.Value : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeySignParameters.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>