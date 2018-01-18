<Type Name="GatewaysExtensions" FullName="Microsoft.PowerBI.Api.V2.GatewaysExtensions">
  <TypeSignature Language="C#" Value="public static class GatewaysExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GatewaysExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.GatewaysExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GatewaysExtensions" />
  <TypeSignature Language="F#" Value="type GatewaysExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddDatasourceUser">
      <MemberSignature Language="C#" Value="public static object AddDatasourceUser (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, Microsoft.PowerBI.Api.V2.Models.UserAccessRight addUserToDatasourceRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object AddDatasourceUser(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, class Microsoft.PowerBI.Api.V2.Models.UserAccessRight addUserToDatasourceRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.AddDatasourceUser(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UserAccessRight)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddDatasourceUser (operations As IGateways, gatewayId As String, datasourceId As String, addUserToDatasourceRequest As UserAccessRight) As Object" />
      <MemberSignature Language="F#" Value="static member AddDatasourceUser : Microsoft.PowerBI.Api.V2.IGateways * string * string * Microsoft.PowerBI.Api.V2.Models.UserAccessRight -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.AddDatasourceUser (operations, gatewayId, datasourceId, addUserToDatasourceRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="addUserToDatasourceRequest" Type="Microsoft.PowerBI.Api.V2.Models.UserAccessRight" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="addUserToDatasourceRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDatasourceUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; AddDatasourceUserAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, Microsoft.PowerBI.Api.V2.Models.UserAccessRight addUserToDatasourceRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; AddDatasourceUserAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, class Microsoft.PowerBI.Api.V2.Models.UserAccessRight addUserToDatasourceRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.AddDatasourceUserAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UserAccessRight,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddDatasourceUserAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * Microsoft.PowerBI.Api.V2.Models.UserAccessRight * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.AddDatasourceUserAsync (operations, gatewayId, datasourceId, addUserToDatasourceRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;AddDatasourceUserAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="addUserToDatasourceRequest" Type="Microsoft.PowerBI.Api.V2.Models.UserAccessRight" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="addUserToDatasourceRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatasource">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.GatewayDatasource CreateDatasource (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest datasourceToGatewayRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.GatewayDatasource CreateDatasource(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, class Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest datasourceToGatewayRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.CreateDatasource(Microsoft.PowerBI.Api.V2.IGateways,System.String,Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateDatasource (operations As IGateways, gatewayId As String, datasourceToGatewayRequest As PublishDatasourceToGatewayRequest) As GatewayDatasource" />
      <MemberSignature Language="F#" Value="static member CreateDatasource : Microsoft.PowerBI.Api.V2.IGateways * string * Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest -&gt; Microsoft.PowerBI.Api.V2.Models.GatewayDatasource" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.CreateDatasource (operations, gatewayId, datasourceToGatewayRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.GatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceToGatewayRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatasourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt; CreateDatasourceAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest datasourceToGatewayRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt; CreateDatasourceAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, class Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest datasourceToGatewayRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.CreateDatasourceAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateDatasourceAsync : Microsoft.PowerBI.Api.V2.IGateways * string * Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.CreateDatasourceAsync (operations, gatewayId, datasourceToGatewayRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;CreateDatasourceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.PublishDatasourceToGatewayRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceToGatewayRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasource">
      <MemberSignature Language="C#" Value="public static object DeleteDatasource (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteDatasource(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasource(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteDatasource (operations As IGateways, gatewayId As String, datasourceId As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteDatasource : Microsoft.PowerBI.Api.V2.IGateways * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasource (operations, gatewayId, datasourceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteDatasourceAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteDatasourceAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteDatasourceAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceAsync (operations, gatewayId, datasourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;DeleteDatasourceAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasourceUser">
      <MemberSignature Language="C#" Value="public static object DeleteDatasourceUser (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, string emailAdress);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteDatasourceUser(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, string emailAdress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceUser(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteDatasourceUser (operations As IGateways, gatewayId As String, datasourceId As String, emailAdress As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteDatasourceUser : Microsoft.PowerBI.Api.V2.IGateways * string * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceUser (operations, gatewayId, datasourceId, emailAdress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="emailAdress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="emailAdress">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasourceUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteDatasourceUserAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, string emailAdress, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteDatasourceUserAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, string emailAdress, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceUserAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteDatasourceUserAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.DeleteDatasourceUserAsync (operations, gatewayId, datasourceId, emailAdress, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;DeleteDatasourceUserAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="emailAdress" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="emailAdress">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceById">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.GatewayDatasource GetDatasourceById (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.GatewayDatasource GetDatasourceById(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceById(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasourceById (operations As IGateways, gatewayId As String, datasourceId As String) As GatewayDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasourceById : Microsoft.PowerBI.Api.V2.IGateways * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.GatewayDatasource" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceById (operations, gatewayId, datasourceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.GatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt; GetDatasourceByIdAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt; GetDatasourceByIdAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceByIdAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourceByIdAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceByIdAsync (operations, gatewayId, datasourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetDatasourceByIdAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.GatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasources">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetDatasources (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetDatasources(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasources(Microsoft.PowerBI.Api.V2.IGateways,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasources (operations As IGateways, gatewayId As String) As ODataResponseListGatewayDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasources : Microsoft.PowerBI.Api.V2.IGateways * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasources (operations, gatewayId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetDatasourcesAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetDatasourcesAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourcesAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesAsync : Microsoft.PowerBI.Api.V2.IGateways * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourcesAsync (operations, gatewayId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetDatasourcesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceStatusById">
      <MemberSignature Language="C#" Value="public static object GetDatasourceStatusById (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object GetDatasourceStatusById(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceStatusById(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasourceStatusById (operations As IGateways, gatewayId As String, datasourceId As String) As Object" />
      <MemberSignature Language="F#" Value="static member GetDatasourceStatusById : Microsoft.PowerBI.Api.V2.IGateways * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceStatusById (operations, gatewayId, datasourceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceStatusByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; GetDatasourceStatusByIdAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; GetDatasourceStatusByIdAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceStatusByIdAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourceStatusByIdAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceStatusByIdAsync (operations, gatewayId, datasourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetDatasourceStatusByIdAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceUsers">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight GetDatasourceUsers (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight GetDatasourceUsers(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceUsers(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasourceUsers (operations As IGateways, gatewayId As String, datasourceId As String) As ODataResponseListUserAccessRight" />
      <MemberSignature Language="F#" Value="static member GetDatasourceUsers : Microsoft.PowerBI.Api.V2.IGateways * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceUsers (operations, gatewayId, datasourceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourceUsersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight&gt; GetDatasourceUsersAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight&gt; GetDatasourceUsersAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceUsersAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourceUsersAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetDatasourceUsersAsync (operations, gatewayId, datasourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetDatasourceUsersAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListUserAccessRight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayById">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Gateway GetGatewayById (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Gateway GetGatewayById(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewayById(Microsoft.PowerBI.Api.V2.IGateways,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayById (operations As IGateways, gatewayId As String) As Gateway" />
      <MemberSignature Language="F#" Value="static member GetGatewayById : Microsoft.PowerBI.Api.V2.IGateways * string -&gt; Microsoft.PowerBI.Api.V2.Models.Gateway" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewayById (operations, gatewayId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Gateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Gateway&gt; GetGatewayByIdAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Gateway&gt; GetGatewayByIdAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewayByIdAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayByIdAsync : Microsoft.PowerBI.Api.V2.IGateways * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Gateway&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewayByIdAsync (operations, gatewayId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetGatewayByIdAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Gateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGateways">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway GetGateways (this Microsoft.PowerBI.Api.V2.IGateways operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway GetGateways(class Microsoft.PowerBI.Api.V2.IGateways operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGateways(Microsoft.PowerBI.Api.V2.IGateways)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGateways (operations As IGateways) As ODataResponseListGateway" />
      <MemberSignature Language="F#" Value="static member GetGateways : Microsoft.PowerBI.Api.V2.IGateways -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGateways operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewaysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway&gt; GetGatewaysAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway&gt; GetGatewaysAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewaysAsync(Microsoft.PowerBI.Api.V2.IGateways,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewaysAsync : Microsoft.PowerBI.Api.V2.IGateways * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.GetGatewaysAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;GetGatewaysAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasource">
      <MemberSignature Language="C#" Value="public static object UpdateDatasource (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest updateDatasourceRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object UpdateDatasource(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest updateDatasourceRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.UpdateDatasource(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasource : Microsoft.PowerBI.Api.V2.IGateways * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.UpdateDatasource (operations, gatewayId, datasourceId, updateDatasourceRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="updateDatasourceRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="updateDatasourceRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; UpdateDatasourceAsync (this Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest updateDatasourceRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; UpdateDatasourceAsync(class Microsoft.PowerBI.Api.V2.IGateways operations, string gatewayId, string datasourceId, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest updateDatasourceRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.GatewaysExtensions.UpdateDatasourceAsync(Microsoft.PowerBI.Api.V2.IGateways,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasourceAsync : Microsoft.PowerBI.Api.V2.IGateways * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.GatewaysExtensions.UpdateDatasourceAsync (operations, gatewayId, datasourceId, updateDatasourceRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.GatewaysExtensions/&lt;UpdateDatasourceAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IGateways" RefType="this" />
        <Parameter Name="gatewayId" Type="System.String" />
        <Parameter Name="datasourceId" Type="System.String" />
        <Parameter Name="updateDatasourceRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourceRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="gatewayId">To be added.</param>
        <param name="datasourceId">To be added.</param>
        <param name="updateDatasourceRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>