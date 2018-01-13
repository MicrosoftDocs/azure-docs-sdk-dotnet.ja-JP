<Type Name="TableMobileAppOptionsExtensions" FullName="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions">
  <TypeSignature Language="C#" Value="public static class TableMobileAppOptionsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableMobileAppOptionsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableMobileAppOptionsExtensions" />
  <TypeSignature Language="F#" Value="type TableMobileAppOptionsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e1f00-101">拡張メソッドを<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-101">Extension methods for <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddTables (config As MobileAppConfiguration) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member AddTables : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config"><span data-ttu-id="e1f00-102">構成オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e1f00-102">The configuration object.</span></span></param>
        <summary>
            <span data-ttu-id="e1f00-103">新しい登録<see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />から派生するすべてのコント ローラーのルートをマップする<see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" />です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-103">Registers a new <see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" /> that maps a route for all controllers that derive from <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e1f00-104">現在の <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-104">The current <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config, Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration tableConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config, class Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration tableConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration,Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddTables (config As MobileAppConfiguration, tableConfig As MobileAppTableConfiguration) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member AddTables : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration * Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables (config, tableConfig)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="We only want this extension to apply to MobileAppConfiguration, not just any AppConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
        <Parameter Name="tableConfig" Type="Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />
      </Parameters>
      <Docs>
        <param name="config"><span data-ttu-id="e1f00-105">構成オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e1f00-105">The configuration object.</span></span></param>
        <param name="tableConfig"></param>
        <summary>
            <span data-ttu-id="e1f00-106">指定した登録<see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-106">Registers the specified <see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e1f00-107">現在の <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-107">The current <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTableControllerConfigProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithTableControllerConfigProvider (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options, Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider tableConfigProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithTableControllerConfigProvider(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options, class Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider tableConfigProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.WithTableControllerConfigProvider(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration,Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WithTableControllerConfigProvider (options As MobileAppConfiguration, tableConfigProvider As ITableControllerConfigProvider) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member WithTableControllerConfigProvider : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration * Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.WithTableControllerConfigProvider (options, tableConfigProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="We only want this extension to apply to MobileAppConfiguration, not just any AppConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
        <Parameter Name="tableConfigProvider" Type="Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="e1f00-108">構成オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e1f00-108">The configuration object.</span></span></param>
        <param name="tableConfigProvider"><span data-ttu-id="e1f00-109">登録するプロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="e1f00-109">The provider to register.</span></span></param>
        <summary>
            <span data-ttu-id="e1f00-110">指定した登録<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />で、<see cref="T:System.Web.Http.HttpConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-110">Registers the specified <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" /> with the <see cref="T:System.Web.Http.HttpConfiguration" />.</span></span>
            <span data-ttu-id="e1f00-111">これを使用して、既定値を上書きする<see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" />構成します。</span><span class="sxs-lookup"><span data-stu-id="e1f00-111">Use this to override the default <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" /> configuration.</span></span>
            </summary>
        <returns><span data-ttu-id="e1f00-112">現在の <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> です。</span><span class="sxs-lookup"><span data-stu-id="e1f00-112">The current <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>