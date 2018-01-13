<Type Name="AsymmetricEncryptedSecret" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret">
  <TypeSignature Language="C#" Value="public class AsymmetricEncryptedSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AsymmetricEncryptedSecret extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class AsymmetricEncryptedSecret" />
  <TypeSignature Language="F#" Value="type AsymmetricEncryptedSecret = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            非対称キーのペアで暗号化のためのもので機密情報を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsymmetricEncryptedSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AsymmetricEncryptedSecret クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsymmetricEncryptedSecret (string value, Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string encryptionCertThumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string encryptionCertThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret : string * Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret (value, encryptionAlgorithm, encryptionCertThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="encryptionAlgorithm" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm" />
        <Parameter Name="encryptionCertThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">シークレットの値です。</param>
        <param name="encryptionAlgorithm">「値」の暗号化に使用されるアルゴリズム。 使用可能な値が含まれます 'None'、'AES256'、'RSAES_PKCS1_v_1_5'。</param>
        <param name="encryptionCertThumbprint">「値」の暗号化に使用された拇印証明書。 値が暗号化されていない場合は、null になります。</param>
        <summary>
            AsymmetricEncryptedSecret クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionAlgorithm As EncryptionAlgorithm" />
      <MemberSignature Language="F#" Value="member this.EncryptionAlgorithm : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または「値」の暗号化に使用されるアルゴリズムを設定します。 使用可能な値が含まれます 'None'、'AES256'、'RSAES_PKCS1_v_1_5'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionCertThumbprint">
      <MemberSignature Language="C#" Value="public string EncryptionCertThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionCertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionCertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionCertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionCertThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionCertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionCertThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または「値」の暗号化に使用された拇印の証明書を設定します。 値が暗号化されていない場合は、null になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="asymmetricEncryptedSecret.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得またはシークレットの値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>