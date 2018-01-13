<Type Name="DistcpSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings">
  <TypeSignature Language="C#" Value="public class DistcpSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DistcpSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class DistcpSettings" />
  <TypeSignature Language="F#" Value="type DistcpSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Distcp 設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistcpSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DistcpSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistcpSettings (object resourceManagerEndpoint, object tempScriptPath, object distcpOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object resourceManagerEndpoint, object tempScriptPath, object distcpOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.#ctor(System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resourceManagerEndpoint As Object, tempScriptPath As Object, Optional distcpOptions As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DistcpSettings : obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DistcpSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.DistcpSettings (resourceManagerEndpoint, tempScriptPath, distcpOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceManagerEndpoint" Type="System.Object" />
        <Parameter Name="tempScriptPath" Type="System.Object" />
        <Parameter Name="distcpOptions" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="resourceManagerEndpoint">Yarn ResourceManager エンドポイントを指定します。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="tempScriptPath">一時 Distcp コマンド スクリプトを格納するために使用する既存のフォルダー パスを指定します。 このスクリプト ファイルは ADF によって生成され、コピー ジョブ完了後に削除されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="distcpOptions">Distcp オプションを指定します。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            DistcpSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistcpOptions">
      <MemberSignature Language="C#" Value="public object DistcpOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DistcpOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.DistcpOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DistcpOptions As Object" />
      <MemberSignature Language="F#" Value="member this.DistcpOptions : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.DistcpOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distcpOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、Distcp オプションを指定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceManagerEndpoint">
      <MemberSignature Language="C#" Value="public object ResourceManagerEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ResourceManagerEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.ResourceManagerEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceManagerEndpoint As Object" />
      <MemberSignature Language="F#" Value="member this.ResourceManagerEndpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.ResourceManagerEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceManagerEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、Yarn ResourceManager エンドポイントを指定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempScriptPath">
      <MemberSignature Language="C#" Value="public object TempScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TempScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.TempScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TempScriptPath As Object" />
      <MemberSignature Language="F#" Value="member this.TempScriptPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.TempScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tempScriptPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、一時 Distcp コマンド スクリプトを格納するために使用する既存のフォルダー パスを指定します。 このスクリプト ファイルは ADF によって生成され、コピー ジョブ完了後に削除されます。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DistcpSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="distcpSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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