<Type Name="AuthenticationTokenSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings">
  <TypeSignature Language="C#" Value="public class AuthenticationTokenSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthenticationTokenSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthenticationTokenSettings" />
  <TypeSignature Language="F#" Value="type AuthenticationTokenSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AuthenticationTokenSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; access = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; access) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.AccessScope})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional access As IList(Of AccessScope) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings access" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt;" />
      </Parameters>
      <Docs>
        <param name="access">バッチ リソースは、トークンがアクセスを付与します。</param>
        <summary>
            AuthenticationTokenSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As IList(Of AccessScope)" />
      <MemberSignature Language="F#" Value="member this.Access : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンがアクセスを許可するバッチのリソースを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            認証トークンは、限られたバッチ サービス操作へのアクセスを許可します。 現在、唯一サポートされているプロパティの値、アクセスは 'ジョブ' は、タスクが含まれているジョブに関連するすべての操作へのアクセスを許可します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>