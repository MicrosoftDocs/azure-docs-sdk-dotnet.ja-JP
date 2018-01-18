<Type Name="MobileServiceLocalSystemTables" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables">
  <TypeSignature Language="C#" Value="public static class MobileServiceLocalSystemTables" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed MobileServiceLocalSystemTables extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceLocalSystemTables" />
  <TypeSignature Language="F#" Value="type MobileServiceLocalSystemTables = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f158e-101">Sync framework によって予約されているローカル ストア内のテーブルの名前</span><span class="sxs-lookup"><span data-stu-id="f158e-101">Names of tables in local store that are reserved by sync framework</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;string&gt; All { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class System.Collections.Generic.IEnumerable`1&lt;string&gt; All" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.All" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property All As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.All : seq&lt;string&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.All" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f158e-102">すべてのシステム テーブルの名前を返します</span><span class="sxs-lookup"><span data-stu-id="f158e-102">Returns the names of all system tables</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Config">
      <MemberSignature Language="C#" Value="public static readonly string Config;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Config" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.Config" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Config As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Config : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.Config" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f158e-103">Sync framework に関連する構成設定を格納するテーブルの名前</span><span class="sxs-lookup"><span data-stu-id="f158e-103">Name of the table that stores configuration settings related to sync framework</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineAll">
      <MemberSignature Language="C#" Value="public static void DefineAll (Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore store);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DefineAll(class Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore store) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.DefineAll(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub DefineAll (store As MobileServiceLocalStore)" />
      <MemberSignature Language="F#" Value="static member DefineAll : Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore -&gt; unit" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.DefineAll store" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore" />
      </Parameters>
      <Docs>
        <param name="store"><span data-ttu-id="f158e-104"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="f158e-104">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></span></span></param>
        <summary>
             <span data-ttu-id="f158e-105">ストア上のすべてのシステム テーブルを定義します。</span><span class="sxs-lookup"><span data-stu-id="f158e-105">Defines all the system tables on the store</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationQueue">
      <MemberSignature Language="C#" Value="public static readonly string OperationQueue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string OperationQueue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.OperationQueue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly OperationQueue As String " />
      <MemberSignature Language="F#" Value=" staticval mutable OperationQueue : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.OperationQueue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f158e-106">操作のキュー項目を格納するテーブルの名前</span><span class="sxs-lookup"><span data-stu-id="f158e-106">Name of the table that stores operation queue items</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public static readonly string Prefix;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Prefix" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Prefix As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Prefix : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.Prefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f158e-107">システム テーブル名で使用されるプレフィックス</span><span class="sxs-lookup"><span data-stu-id="f158e-107">Prefix used on system table names</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncErrors">
      <MemberSignature Language="C#" Value="public static readonly string SyncErrors;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string SyncErrors" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.SyncErrors" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly SyncErrors As String " />
      <MemberSignature Language="F#" Value=" staticval mutable SyncErrors : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalSystemTables.SyncErrors" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f158e-108">同期のエラーを格納するテーブルの名前</span><span class="sxs-lookup"><span data-stu-id="f158e-108">Name of the table that stores sync errors</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>