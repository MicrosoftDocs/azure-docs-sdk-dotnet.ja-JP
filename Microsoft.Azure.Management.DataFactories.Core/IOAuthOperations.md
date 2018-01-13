<Type Name="IOAuthOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations">
  <TypeSignature Language="C#" Value="public interface IOAuthOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOAuthOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOAuthOperations" />
  <TypeSignature Language="F#" Value="type IOAuthOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            OAuth 承認のための操作。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string linkedServiceType, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string linkedServiceType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;" Usage="iOAuthOperations.GetAsync (resourceGroupName, dataFactoryName, linkedServiceType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceType" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="linkedServiceType">
            OAuth の種類のリンクされたサービス。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            OAuth 認証セッションを取得します。
            </summary>
        <returns>
            認証セッションの Get 操作応答します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>