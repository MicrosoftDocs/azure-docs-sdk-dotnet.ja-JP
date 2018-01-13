<Type Name="ClusterVersionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ClusterVersionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ClusterVersionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ClusterVersionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ClusterVersionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ClusterVersionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt; List (this Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string location, string environment);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt; List(class Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string location, string environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.List(Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IClusterVersionsOperations, location As String, environment As String) As IPage(Of ClusterCodeVersionsResult)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.List (operations, location, environment)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            クラスターのコードのバージョンの場所、これは、クラスターの場所と異なる
            </param>
        <param name="environment">
            クラスター オペレーティング システムで、既定では、すべてを意味します。 使用可能な値が含まれます: 'Default'、'Windows'、'Linux'
            </param>
        <summary>
            場所ごとのクラスターのコードのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt; ListAsync (this Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string location, string environment, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt; ListAsync(class Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string location, string environment, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListAsync (operations, location, environment, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            クラスターのコードのバージョンの場所、これは、クラスターの場所と異なる
            </param>
        <param name="environment">
            クラスター オペレーティング システムで、既定では、すべてを意味します。 使用可能な値が含まれます: 'Default'、'Windows'、'Linux'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            場所ごとのクラスターのコードのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt; ListNext (this Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt; ListNext(class Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IClusterVersionsOperations, nextPageLink As String) As IPage(Of ClusterCodeVersionsResult)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            場所ごとのクラスターのコードのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClusterVersionsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            場所ごとのクラスターのコードのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>