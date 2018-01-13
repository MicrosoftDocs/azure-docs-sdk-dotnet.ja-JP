<Type Name="LocationOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.LocationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LocationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LocationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.LocationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LocationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LocationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            LocationOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.LocationOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Batch.ILocationOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As ILocationOperations, locationName As String, name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Batch.ILocationOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.Batch.LocationOperationsExtensions.CheckNameAvailability (operations, locationName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ILocationOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="locationName">
            名前チェックの目的の地域。
            </param>
        <param name="name">
            名前の可用性を確認するには
            </param>
        <summary>
            指定した領域で Batch アカウント名が使用できるかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.LocationOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Batch.ILocationOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Batch.ILocationOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.Batch.LocationOperationsExtensions.CheckNameAvailabilityAsync (operations, locationName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.LocationOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ILocationOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="locationName">
            名前チェックの目的の地域。
            </param>
        <param name="name">
            名前の可用性を確認するには
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した領域で Batch アカウント名が使用できるかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotas">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchLocationQuota GetQuotas (this Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchLocationQuota GetQuotas(class Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.LocationOperationsExtensions.GetQuotas(Microsoft.Azure.Management.Batch.ILocationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetQuotas (operations As ILocationOperations, locationName As String) As BatchLocationQuota" />
      <MemberSignature Language="F#" Value="static member GetQuotas : Microsoft.Azure.Management.Batch.ILocationOperations * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchLocationQuota" Usage="Microsoft.Azure.Management.Batch.LocationOperationsExtensions.GetQuotas (operations, locationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchLocationQuota</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ILocationOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="locationName">
            バッチ サービスのクォータを取得する対象の領域。
            </param>
        <summary>
            指定された場所に、指定されたサブスクリプションのバッチ サービスのクォータを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt; GetQuotasAsync (this Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt; GetQuotasAsync(class Microsoft.Azure.Management.Batch.ILocationOperations operations, string locationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.LocationOperationsExtensions.GetQuotasAsync(Microsoft.Azure.Management.Batch.ILocationOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotasAsync : Microsoft.Azure.Management.Batch.ILocationOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;" Usage="Microsoft.Azure.Management.Batch.LocationOperationsExtensions.GetQuotasAsync (operations, locationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.LocationOperationsExtensions/&lt;GetQuotasAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ILocationOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="locationName">
            バッチ サービスのクォータを取得する対象の領域。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された場所に、指定されたサブスクリプションのバッチ サービスのクォータを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>