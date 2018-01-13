<Type Name="TransparentDataEncryptionsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransparentDataEncryptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TransparentDataEncryptionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption CreateOrUpdate (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption CreateOrUpdate(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITransparentDataEncryptionsOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As TransparentDataEncryption) As TransparentDataEncryption" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータを設定すると、暗号化が適用されるデータベースの名前。
            </param>
        <param name="parameters">
            作成または更新の透過的なデータ暗号化の必要なパラメーター。
            </param>
        <summary>
            作成するか、データベースの透過的なデータ暗号化の構成を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータを設定すると、暗号化が適用されるデータベースの名前。
            </param>
        <param name="parameters">
            作成または更新の透過的なデータ暗号化の必要なパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、データベースの透過的なデータ暗号化の構成を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption Get (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption Get(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITransparentDataEncryptionsOperations, resourceGroupName As String, serverName As String, databaseName As String) As TransparentDataEncryption" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータ暗号化が適用されるデータベースの名前。
            </param>
        <summary>
            データベースの透過的なデータ暗号化の構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; GetAsync (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; GetAsync(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータ暗号化が適用されるデータベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データベースの透過的なデータ暗号化の構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>