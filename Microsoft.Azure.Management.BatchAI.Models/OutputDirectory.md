<Type Name="OutputDirectory" FullName="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory">
  <TypeSignature Language="C#" Value="public class OutputDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputDirectory" />
  <TypeSignature Language="F#" Value="type OutputDirectory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ジョブの出力ディレクトリです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OutputDirectory クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory (string id, string pathPrefix, string pathSuffix = null, string type = null, Nullable&lt;bool&gt; createNew = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string pathPrefix, string pathSuffix, string type, valuetype System.Nullable`1&lt;bool&gt; createNew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, pathPrefix As String, Optional pathSuffix As String = null, Optional type As String = null, Optional createNew As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory : string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" Usage="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory (id, pathPrefix, pathSuffix, type, createNew)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="pathSuffix" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="createNew" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">出力ディレクトリの名前。</param>
        <param name="pathPrefix">出力ディレクトリを作成するプレフィックスのパス。</param>
        <param name="pathSuffix">出力ディレクトリを作成するサフィックス パスです。</param>
        <param name="type">ジョブの出力ディレクトリの種類を指定する列挙です。</param>
        <param name="createNew">新しいディレクトリを作成する場合は true です。</param>
        <summary>
            OutputDirectory クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CreateNew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CreateNew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CreateNew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createNew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を新しいディレクトリを作成する場合。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は true です。 False の場合、ディレクトリは作成されていないと、ユーザーが指定したディレクトリのパスを指定できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力ディレクトリの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            AZ_BATCHAI_OUTPUT_id 環境変数として、ジョブの利用可能な場合もなります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPrefix">
      <MemberSignature Language="C#" Value="public string PathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力ディレクトリを作成するプレフィックスのパスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            注: これは、プレフィックスへの絶対パスです。 例: 
            $AZ_BATCHAI_MOUNT_ROOT/MyNFS/MyLogs です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力ディレクトリを作成するサフィックスのパスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            出力ディレクトリを作成するサフィックス パスです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力ディレクトリのジョブの種類を指定する列挙体を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、カスタムです。 使用可能な値は、モデル、ログ、概要、およびカスタムです。 ユーザーは、1 つのディレクトリに複数の列挙型を使用できます。 例: outPutType 'モデルでは、ログ、Summary' を = です。 使用可能な値が含まれます: 'モデル'、'ログ'、'概要'、'custom'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputDirectory.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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
  </Members>
</Type>