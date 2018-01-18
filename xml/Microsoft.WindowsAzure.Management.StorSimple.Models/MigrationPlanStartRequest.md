<Type Name="MigrationPlanStartRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest">
  <TypeSignature Language="C#" Value="public class MigrationPlanStartRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlanStartRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlanStartRequest" />
  <TypeSignature Language="F#" Value="type MigrationPlanStartRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="01e86-101">このクラスは、移行計画の開始の要求本文を表します。</span><span class="sxs-lookup"><span data-stu-id="01e86-101">This class represents request body of start migration plan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanStartRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01e86-102">MigrationPlanStartRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01e86-102">Initializes a new instance of the MigrationPlanStartRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanStartRequest (string configId, System.Collections.Generic.List&lt;string&gt; dataContainerNameList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configId, class System.Collections.Generic.List`1&lt;string&gt; dataContainerNameList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.#ctor(System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configId As String, dataContainerNameList As List(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest : string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest (configId, dataContainerNameList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="dataContainerNameList" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="configId">To be added.</param>
        <param name="dataContainerNameList">To be added.</param>
        <summary>
            <span data-ttu-id="01e86-103">必須の引数で MigrationPlanStartRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01e86-103">Initializes a new instance of the MigrationPlanStartRequest class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigId">
      <MemberSignature Language="C#" Value="public string ConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.ConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigId As String" />
      <MemberSignature Language="F#" Value="member this.ConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.ConfigId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01e86-104">必須。</span><span class="sxs-lookup"><span data-stu-id="01e86-104">Required.</span></span> <span data-ttu-id="01e86-105">取得または構成のインポート中に渡されるレガシ アプライアンス構成 id を設定します。</span><span class="sxs-lookup"><span data-stu-id="01e86-105">Gets or sets legacy appliance config id passed while importing the config.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerNameList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DataContainerNameList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DataContainerNameList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.DataContainerNameList" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerNameList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DataContainerNameList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest.DataContainerNameList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01e86-106">必須。</span><span class="sxs-lookup"><span data-stu-id="01e86-106">Required.</span></span> <span data-ttu-id="01e86-107">取得または設定の移行計画を処理する必要があるデータ コンテナーのリストの名前。</span><span class="sxs-lookup"><span data-stu-id="01e86-107">Gets or sets list name of data containers which needs to be processed for migration plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>