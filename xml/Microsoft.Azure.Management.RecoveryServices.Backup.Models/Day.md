<Type Name="Day" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day">
  <TypeSignature Language="C#" Value="public class Day" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Day extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day" />
  <TypeSignature Language="VB.NET" Value="Public Class Day" />
  <TypeSignature Language="F#" Value="type Day = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc3bb-101">週の曜日。</span><span class="sxs-lookup"><span data-stu-id="dc3bb-101">Day of the week.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Day ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc3bb-102">Day クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc3bb-102">Initializes a new instance of the Day class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Day (Nullable&lt;int&gt; date = null, Nullable&lt;bool&gt; isLast = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; date, valuetype System.Nullable`1&lt;bool&gt; isLast) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.#ctor(System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional date As Nullable(Of Integer) = null, Optional isLast As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day : Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day (date, isLast)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="date" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isLast" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="date"><span data-ttu-id="dc3bb-103">月の日付</span><span class="sxs-lookup"><span data-stu-id="dc3bb-103">Date of the month</span></span></param>
        <param name="isLast"><span data-ttu-id="dc3bb-104">日付の月の最後の日付がかどうか</span><span class="sxs-lookup"><span data-stu-id="dc3bb-104">Whether Date is last date of month</span></span></param>
        <summary>
            <span data-ttu-id="dc3bb-105">Day クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc3bb-105">Initializes a new instance of the Day class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Date">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Date { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Date" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.Date" />
      <MemberSignature Language="VB.NET" Value="Public Property Date As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Date : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.Date" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="date")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc3bb-106">取得または月の日付を設定</span><span class="sxs-lookup"><span data-stu-id="dc3bb-106">Gets or sets date of the month</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLast">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsLast { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsLast" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.IsLast" />
      <MemberSignature Language="VB.NET" Value="Public Property IsLast As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsLast : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day.IsLast" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isLast")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc3bb-107">取得または日付が月の最後の日付であるかどうかを設定</span><span class="sxs-lookup"><span data-stu-id="dc3bb-107">Gets or sets whether Date is last date of month</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>